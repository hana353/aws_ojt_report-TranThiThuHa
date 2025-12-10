---
title: "Week 5 Worklog"

weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:

* Learn NoSQL database with Amazon DynamoDB.
* Understand in-memory caching with Amazon ElastiCache.
* Master content delivery with Amazon CloudFront.
* Learn edge computing with CloudFront and Lambda@Edge.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn Amazon DynamoDB basics: <br>&emsp; + Tables, Items, Attributes <br>&emsp; + Primary Keys (Partition, Sort) <br>&emsp; + Read/Write Capacity <br> - **Practice:** Create DynamoDB table    | 06/10/2025 | 06/10/2025      | <https://000060.awsstudygroup.com/> |
| Tue | - Learn DynamoDB advanced features: <br>&emsp; + Secondary Indexes (GSI, LSI) <br>&emsp; + DynamoDB Streams <br>&emsp; + TTL <br> - **Practice:** Query and Scan operations                        | 07/10/2025 | 07/10/2025      | <https://000060.awsstudygroup.com/> |
| Wed | - Learn Amazon ElastiCache: <br>&emsp; + Redis vs Memcached <br>&emsp; + Cluster configurations <br>&emsp; + Caching strategies <br> - **Practice:** Create ElastiCache Redis cluster              | 08/10/2025 | 08/10/2025      | <https://000061.awsstudygroup.com/> |
| Thu | - Learn Amazon CloudFront: <br>&emsp; + CDN concepts <br>&emsp; + Distributions, Origins <br>&emsp; + Cache behaviors <br> - **Practice:** Create CloudFront distribution for S3                   | 09/10/2025 | 09/10/2025      | <https://000094.awsstudygroup.com/> |
| Fri | - Learn CloudFront & Lambda@Edge: <br>&emsp; + Edge functions <br>&emsp; + Use cases (URL rewrite, auth) <br>&emsp; + Deployment <br> - **Practice:** Implement Lambda@Edge function               | 10/10/2025 | 10/10/2025      | <https://000095.awsstudygroup.com/> |


### Week 5 Achievements:

* Mastered Amazon DynamoDB NoSQL database:
  * Created DynamoDB tables with partition and sort keys
  * Understood provisioned vs on-demand capacity modes
  * Performed CRUD operations using AWS Console and CLI
  * Implemented Global Secondary Indexes (GSI) for flexible queries
  * Configured DynamoDB Streams for event-driven architectures
  * Set up TTL for automatic data expiration

* Learned Amazon ElastiCache for in-memory caching:
  * Understood differences between Redis and Memcached
  * Created ElastiCache Redis cluster in VPC
  * Configured security groups for cache access
  * Implemented caching strategies (lazy loading, write-through)
  * Connected application to ElastiCache from EC2

* Implemented Amazon CloudFront CDN:
  * Created CloudFront distribution with S3 origin
  * Configured cache behaviors and TTL settings
  * Set up custom domain with SSL certificate (ACM)
  * Implemented Origin Access Control (OAC) for S3
  * Understood edge locations and regional caches

* Explored CloudFront with Lambda@Edge:
  * Understood edge computing concepts
  * Created Lambda@Edge functions for request/response manipulation
  * Implemented URL rewrites and redirects
  * Configured viewer request and origin request triggers
  * Deployed edge functions globally
