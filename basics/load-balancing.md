Load Balancing (LB)
====

Help scale horizontally across an ever-increasing number of servers.

Load Balancer (LB) is another critical component of any distributed system. It helps to spread the traffic across a cluster of servers to improve responsiveness and availability of applications, websites or databases. LB also keeps track of the status of all the resources while distributing requests. If a server is not available to take new requests or is not responding or has elevated error rate, LB will stop sending traffic to such a server.

Typically a load balancer sits between the client and the server accepting incoming network and application traffic and distributing the traffic across multiple backend servers using various algorithms. By balancing application requests across multiple servers, a load balancer reduces individual server load and prevents any one application server from becoming a single point of failure, thus improving overall application availability and responsiveness.

![](../img/load-balancer-1a.svg)

## LB locations
- Between user and web server
- Between web servers and an internal platform layer (application servers, cache servers)
- Between internal platform layer and database

## Algorithms
- Least connection
- Least response time
- Least bandwidth
- Round robin
- Weighted round robin
- IP hash

## Implementation
- Smart clients
- Hardware load balancers
- Software load balancers
