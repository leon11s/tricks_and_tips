# System Design

## Topics
1. Network Protocols
    - Machines in distributed systems communicate with each another over a network.
    - Basic understanding of low-level networking
    - Protocols (IP, TCP, UDP, DNS, and HTTP(S))
2. Storage
    - Information storage is a fundamental component of every distributed system.
    - volatile vs. nonvolatile memory
    - the concept of a database
3. Availability
    - Most distributed systems need to be highly available.
    - how to measure a system's availability 
    - how to increase a system's availability 
    - how to use redundancy
4. Cache
    - Caches store responses to network requests or computationally expensive operation results.
    - cache hit and miss terminology
    - cache eviction policies
    - content delivery networks
5. Latency and Throughput
    - These are key parameters to evaluate the performance of a distributed system.
    - latencies of the most common operations
    - back-of-the-envelope calculations
6. Proxies and Load Balancers
    - Proxies are intermediary servers used in every system.
    - forward and reverse proxies
    - use of reverse proxies as load balancers
    - load balancer's server selection strategies
7. Hashing
    - Hashing is helpful for the elastic scaling of cache servers and data partitioning.
    - consistent hashin
    - rendezvous hashing    
8. Relational Databases
    - These are structured databases storing data in tabular format and supporting SQL queries.
    - indexing
    - ACID transactions
    - strong vs. eventual consistency
9. Non Relational Databases
    - Key-value databases (i.e., Redis, Zookeeper ) are often used for caching and configuration.
    - blob storage (S3)
    - time-series databases
    - graph database (Neo4j)
    - spatial databases and quadtrees 
10. Replication and Sharding
    - These are standard techniques to increase availability and performance.
    - how to duplicate data on multiple servers to increase redundancy
    - how to divide data across multiple servers to increase throughput 
11. Leader Election
    - This is how a cluster of servers selects a leader responsible for all the primary operations.
    - what is a consensus algorithm
    - how Paxos or Raft works 
12. Polling and Streaming
    - These are the most common techniques to obtain data from a server.
    - how to fetch data at regular intervals (polling)
    - how to get a continuous data feed (streaming) 
13. Logging and Monitoring
    - Every system needs to measure performance and troubleshoot issues.
    - how to collect and log events information
    - how to get visibility of the system key metrics
    - how to aggregate human readable metrics 
14. Publish-Subscribe
    - This is a widely used messaging pattern.
    - how pub-sub works
    - what are idempotent operations
    - popular frameworks like Apache Kafka 
15. Peer-To-Peer networks
    - These are machines splitting a workload between them to complete it the fastest way.
    - what is a gossip protocol
    - use cases of such networks 
16. Rate Limiting
    - Limiting the number of requests sent to or received by a system is essential.
    - how rate limiting can prevent DDoS attacks
    - how to implement rate-limiting strategies (i.e., with Redis) 
17. MapReduce
    - This is a popular framework for processing large distributed datasets efficiently and in a fault-tolerant way.
    - what is a distributed file system
    - popular distributed file systems implementations (i.e., HDFS) 
18. API Design
    - the basics of Web API design
    - the concept of CRUD operations 

## Examples
- [China Train ticket booking system](./examples/china_train_ticket_booking_system.md)

## Courses

## Learning platforms

## Blogs
- [Simplify Your Microservices Architecture With a Data API](https://dzone.com/articles/simplify-your-microservices-architecture-with-a-da)

## Books

## Videos
- [System Design for Beginners Course](https://www.youtube.com/watch?v=m8Icp_Cid5o&t=2s): This course is a detailed introduction to system design for software developers and engineers.

## Tricks

