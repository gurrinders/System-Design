# System Design: Concepts and Resources

This repository contains key concepts and resources related to system design. Below is a curated list of topics, each accompanied by a helpful reference link for deeper understanding.

---

## 1. Performance Metrics
- **Latency vs Throughput**: 
  - **Latency**: Measures delay in network communication (time taken for data transfer). High latency indicates longer delays, while low latency indicates quicker response times.
  - **Throughput**: Measures the volume of data successfully transmitted over a network in a specific time period. It reflects data packet delivery success and loss.
  - [Read More](https://aws.amazon.com/compare/the-difference-between-throughput-and-latency/)

---

## 2. Core Concepts
- CAP Theorem
- The CAP theorem is a belief from theoretical computer science about distributed data stores that claims, in the event of a network failure on a distributed database, it is possible to 
  provide either consistency or availability—but not both.
  
  The CAP Theorem is comprised of three components (hence its name) as they relate to distributed data stores:
  1.  Consistency- All reads receive the most recent write or an error.
  2.  Availability- All reads contain data, but it might not be the most recent.
  3.  Partition tolerance- The system continues to operate despite network failures (ie; dropped partitions, slow network connections, or unavailable network connections between nodes.)

  - [Read More](https://lnkd.in/gV7NunUD)
  
- [ACID Transactions]
  - [Read More](https://lnkd.in/gpQMxV9u)
  
- [Consistent Hashing]
   - [Read More](https://lnkd.in/gaCVWBJM)
 
- [Rate Limiting]
   - [Read More](https://lnkd.in/gjkrHkGu)
     
- [Microservices Architecture]
   - (https://lnkd.in/gy3kRzep)
  
- [API Design]
   - (https://lnkd.in/ghcbQySg
  
- [Strong vs Eventual Consistency]
   - (https://lnkd.in/g2ACr56Q)
  
- [Synchronous vs Asynchronous Communications]
   - (https://lnkd.in/gYZ8Acth)
  
- [REST vs RPC]
  - (https://lnkd.in/gs7htCMG)
  
- [Batch Processing vs Stream Processing]
   - (https://lnkd.in/gBKHzqAe)

---

## 3. Reliability and Scalability
- [Fault Tolerance](https://lnkd.in/ggzdZVhM)
- [Consensus Algorithms](https://lnkd.in/gUcVEhUx)
- [Gossip Protocol](https://lnkd.in/gvkckQGY)
- [Serverless Architecture](https://lnkd.in/g3EYA3nz)
- [Service Discovery](https://lnkd.in/gt84khQG)
- [Disaster Recovery](https://lnkd.in/grpEFGfD)
- [Distributed Tracing](https://lnkd.in/ga5FJuH2)
- [Horizontal vs Vertical Scaling](https://lnkd.in/eQc9FRjf)

---

## 4. Data Management
- [Content Delivery Network (CDN)](https://lnkd.in/e7reQ4VF)
- [Domain Name System (DNS)](https://lnkd.in/es8Fp7Q5)
- [Caching](https://lnkd.in/eZkyjptm)
- [Distributed Caching](https://lnkd.in/e4AHNSeT)
- [Load Balancing](https://lnkd.in/eWdwhGap)
- [SQL vs NoSQL](https://lnkd.in/es6vJwit)
- [Database Indexing](https://lnkd.in/ebKcznNJ)
- [Consistency Patterns](https://lnkd.in/eTZ5dHQx)
- [Database Scaling](https://lnkd.in/egFC33Zk)
- [Data Replication](https://lnkd.in/ehZjnuWx)
- [Data Redundancy](https://lnkd.in/eUCxcXr2)
- [Database Sharding](https://lnkd.in/eF_2KNKT)

---

## 5. System Reliability and Optimization
- [HeartBeat Mechanism](https://lnkd.in/eRBRtfk9)
- [Circuit Breaker](https://lnkd.in/eStETWQA)
- [Idempotency](https://lnkd.in/eSYjuq-b)
- [Failover Strategies](https://lnkd.in/eftew-CE)
- [Proxy Server](https://lnkd.in/eVCYxMZQ)
- [Message Queues](https://lnkd.in/eVeVWT3a)
- [WebSockets](https://lnkd.in/eA4zYkjF)
- [Bloom Filters](https://lnkd.in/eG3xPV-x)
- [API Gateway](https://lnkd.in/e-zCR3ft)
- [Distributed Locking](https://lnkd.in/eXsuuthN)
- [Checksum Mechanism](https://lnkd.in/ed4j8cfk)

---

## 6. Microservices Best Practices
- [Microservices Guidelines](https://lnkd.in/ea8hcbqp)

---

Feel free to explore the resources and enhance your understanding of system design principles!

This version organizes the content into sections, improves readability, and makes the file more user-friendly. Let me know if you’d like further adjustments!
