---
title: "Worklog Tuần 6"
date: "`r Sys.Date()`"
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Tìm hiểu serverless computing với AWS Lambda.
* Nắm vững advanced monitoring với CloudWatch và Grafana.
* Hiểu resource organization với Tags và Resource Groups.
* Tìm hiểu systems management với AWS Systems Manager.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS Lambda cơ bản: <br>&emsp; + Khái niệm Serverless <br>&emsp; + Tạo function <br>&emsp; + Triggers và events <br> - **Thực hành:** Tạo Lambda function với API Gateway                      | 13/10/2025   | 13/10/2025      | <https://000022.awsstudygroup.com/> |
| 3   | - Tìm hiểu Lambda nâng cao: <br>&emsp; + Environment variables <br>&emsp; + Layers và versions <br>&emsp; + Concurrency <br> - **Thực hành:** Lambda với S3 và DynamoDB triggers                         | 14/10/2025   | 14/10/2025      | <https://000022.awsstudygroup.com/> |
| 4   | - Tìm hiểu Advanced Monitoring: <br>&emsp; + CloudWatch advanced metrics <br>&emsp; + Grafana integration <br>&emsp; + Custom dashboards <br> - **Thực hành:** Thiết lập Grafana với CloudWatch          | 15/10/2025   | 15/10/2025      | <https://000029.awsstudygroup.com/> |
| 5   | - Tìm hiểu Tags và Resource Groups: <br>&emsp; + Tagging strategies <br>&emsp; + Resource Groups <br>&emsp; + Tag-based access control <br> - **Thực hành:** Triển khai tagging strategy                 | 16/10/2025   | 16/10/2025      | <https://000027.awsstudygroup.com/> |
| 6   | - Tìm hiểu AWS Systems Manager: <br>&emsp; + Session Manager <br>&emsp; + Parameter Store <br>&emsp; + Run Command <br> - **Thực hành:** Quản lý EC2 với Systems Manager                                 | 17/10/2025   | 17/10/2025      | <https://000031.awsstudygroup.com/> |


### Kết quả đạt được tuần 6:

* Nắm vững AWS Lambda serverless computing:
  * Tạo Lambda functions bằng Python/Node.js
  * Cấu hình API Gateway làm Lambda trigger
  * Thiết lập S3 và DynamoDB event triggers
  * Quản lý environment variables và secrets
  * Hiểu Lambda layers cho code reuse
  * Cấu hình concurrency và memory settings

* Tìm hiểu advanced monitoring với CloudWatch và Grafana:
  * Tạo custom CloudWatch metrics
  * Thiết lập Grafana cho advanced visualization
  * Xây dựng custom dashboards cho monitoring
  * Cấu hình alerts và notifications
  * Triển khai log insights queries

* Triển khai Tags và Resource Groups:
  * Thiết kế tagging strategy cho organization
  * Tạo Resource Groups cho management
  * Triển khai tag-based access control với IAM
  * Sử dụng tags cho cost allocation
  * Tự động hóa tagging với AWS Config

* Nắm vững AWS Systems Manager:
  * Kết nối tới EC2 không cần SSH bằng Session Manager
  * Lưu trữ secrets trong Parameter Store
  * Thực thi commands trên nhiều instances với Run Command
  * Thiết lập Patch Manager cho automated patching
  * Tạo automation documents cho routine tasks


