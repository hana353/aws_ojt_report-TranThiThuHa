---
title: "Worklog Tuần 5"

weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Tìm hiểu NoSQL database với Amazon DynamoDB.
* Hiểu in-memory caching với Amazon ElastiCache.
* Nắm vững content delivery với Amazon CloudFront.
* Tìm hiểu edge computing với CloudFront và Lambda@Edge.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Amazon DynamoDB cơ bản: <br>&emsp; + Tables, Items, Attributes <br>&emsp; + Primary Keys (Partition, Sort) <br>&emsp; + Read/Write Capacity <br> - **Thực hành:** Tạo DynamoDB table         | 06/10/2025   | 06/10/2025      | <https://000060.awsstudygroup.com/> |
| 3   | - Tìm hiểu DynamoDB tính năng nâng cao: <br>&emsp; + Secondary Indexes (GSI, LSI) <br>&emsp; + DynamoDB Streams <br>&emsp; + TTL <br> - **Thực hành:** Query và Scan operations                          | 07/10/2025   | 07/10/2025      | <https://000060.awsstudygroup.com/> |
| 4   | - Tìm hiểu Amazon ElastiCache: <br>&emsp; + Redis vs Memcached <br>&emsp; + Cluster configurations <br>&emsp; + Caching strategies <br> - **Thực hành:** Tạo ElastiCache Redis cluster                  | 08/10/2025   | 08/10/2025      | <https://000061.awsstudygroup.com/> |
| 5   | - Tìm hiểu Amazon CloudFront: <br>&emsp; + Khái niệm CDN <br>&emsp; + Distributions, Origins <br>&emsp; + Cache behaviors <br> - **Thực hành:** Tạo CloudFront distribution cho S3                       | 09/10/2025   | 09/10/2025      | <https://000094.awsstudygroup.com/> |
| 6   | - Tìm hiểu CloudFront & Lambda@Edge: <br>&emsp; + Edge functions <br>&emsp; + Use cases (URL rewrite, auth) <br>&emsp; + Deployment <br> - **Thực hành:** Implement Lambda@Edge function                 | 10/10/2025   | 10/10/2025      | <https://000130.awsstudygroup.com/> |


### Kết quả đạt được tuần 5:

* Nắm vững Amazon DynamoDB NoSQL database:
  * Tạo DynamoDB tables với partition và sort keys
  * Hiểu provisioned vs on-demand capacity modes
  * Thực hiện CRUD operations sử dụng AWS Console và CLI
  * Triển khai Global Secondary Indexes (GSI) cho flexible queries
  * Cấu hình DynamoDB Streams cho event-driven architectures
  * Thiết lập TTL cho automatic data expiration

* Tìm hiểu Amazon ElastiCache cho in-memory caching:
  * Hiểu sự khác biệt giữa Redis và Memcached
  * Tạo ElastiCache Redis cluster trong VPC
  * Cấu hình security groups cho cache access
  * Triển khai caching strategies (lazy loading, write-through)
  * Kết nối application tới ElastiCache từ EC2

* Triển khai Amazon CloudFront CDN:
  * Tạo CloudFront distribution với S3 origin
  * Cấu hình cache behaviors và TTL settings
  * Thiết lập custom domain với SSL certificate (ACM)
  * Triển khai Origin Access Control (OAC) cho S3
  * Hiểu edge locations và regional caches

* Khám phá CloudFront với Lambda@Edge:
  * Hiểu khái niệm edge computing
  * Tạo Lambda@Edge functions cho request/response manipulation
  * Triển khai URL rewrites và redirects
  * Cấu hình viewer request và origin request triggers
  * Deploy edge functions globally


