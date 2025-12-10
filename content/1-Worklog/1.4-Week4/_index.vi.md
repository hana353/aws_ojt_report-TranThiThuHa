---
title: "Worklog Tuần 4"

weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Tìm hiểu dịch vụ compute đơn giản với Amazon Lightsail.
* Hiểu cách mở rộng ứng dụng với EC2 Auto Scaling.
* Nắm vững giám sát và quan sát với Amazon CloudWatch.
* Tìm hiểu quản lý DNS với Amazon Route 53.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Amazon Lightsail: <br>&emsp; + So sánh Lightsail vs EC2 <br>&emsp; + Instances, Blueprints <br>&emsp; + Networking & Storage <br> - **Thực hành:** Deploy WordPress trên Lightsail           | 29/09/2025   | 29/09/2025      | <https://000045.awsstudygroup.com/> |
| 3   | - Tìm hiểu Lightsail Containers: <br>&emsp; + Container services <br>&emsp; + Deployment configurations <br>&emsp; + Public endpoints <br> - **Thực hành:** Deploy containerized app trên Lightsail    | 30/09/2025   | 30/09/2025      | <https://000046.awsstudygroup.com/> |
| 4   | - Tìm hiểu EC2 Auto Scaling: <br>&emsp; + Launch Templates <br>&emsp; + Auto Scaling Groups <br>&emsp; + Scaling policies <br> - **Thực hành:** Tạo Auto Scaling Group với scaling policies             | 01/10/2025   | 01/10/2025      | <https://000006.awsstudygroup.com/> |
| 5   | - Tìm hiểu Amazon CloudWatch: <br>&emsp; + Metrics và Alarms <br>&emsp; + Logs và Dashboards <br>&emsp; + Events và Rules <br> - **Thực hành:** Thiết lập CloudWatch alarms cho EC2                     | 02/10/2025   | 02/10/2025      | <https://000008.awsstudygroup.com/> |
| 6   | - Tìm hiểu Amazon Route 53: <br>&emsp; + Khái niệm DNS <br>&emsp; + Hosted zones <br>&emsp; + Routing policies <br> - **Thực hành:** Cấu hình custom domain với Route 53                                | 03/10/2025   | 03/10/2025      | <https://000010.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:

* Nắm vững Amazon Lightsail cho compute đơn giản:
  * Hiểu sự khác biệt giữa Lightsail và EC2
  * Tạo Lightsail instances với các blueprints khác nhau
  * Deploy website WordPress trên Lightsail
  * Cấu hình static IP và DNS cho Lightsail instance

* Tìm hiểu Lightsail Containers:
  * Tạo container service trên Lightsail
  * Deploy ứng dụng containerized
  * Cấu hình public endpoints và custom domains
  * Hiểu quy trình container deployment

* Triển khai EC2 Auto Scaling:
  * Tạo Launch Templates cho EC2 instances
  * Cấu hình Auto Scaling Groups (ASG)
  * Thiết lập scaling policies (target tracking, step scaling)
  * Test scaling dựa trên CPU utilization
  * Hiểu desired, minimum, và maximum capacity

* Nắm vững Amazon CloudWatch cho monitoring:
  * Khám phá default EC2 metrics (CPU, Network, Disk)
  * Tạo custom CloudWatch alarms
  * Thiết lập alarm notifications qua SNS
  * Tạo CloudWatch dashboards để visualization
  * Cấu hình CloudWatch Logs cho application logging

* Cấu hình Amazon Route 53 cho DNS:
  * Hiểu khái niệm DNS (A, CNAME, Alias records)
  * Tạo hosted zones cho domains
  * Cấu hình các routing policies (Simple, Weighted, Latency)
  * Tích hợp Route 53 với các AWS services khác (ALB, S3, CloudFront)


