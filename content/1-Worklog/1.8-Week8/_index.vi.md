---
title: "Worklog Tuần 8"
date: "`r Sys.Date()`"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Tìm hiểu truy cập server từ xa với Systems Manager Session Manager.
* Nắm vững giám sát mạng với VPC Flow Logs.
* Hiểu quản lý service quotas.
* Tìm hiểu quản lý chi phí và usage trên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Session Manager: <br>&emsp; + Secure shell access không cần SSH <br>&emsp; + IAM policies cho Session Manager <br>&emsp; + Logging và auditing <br> - **Thực hành:** Kết nối EC2 qua Session Manager | 27/10/2025   | 27/10/2025      | <https://000058.awsstudygroup.com/> |
| 3   | - Tìm hiểu VPC Flow Logs: <br>&emsp; + Khái niệm Flow log <br>&emsp; + Log destinations (S3, CloudWatch) <br>&emsp; + Phân tích network traffic <br> - **Thực hành:** Bật và phân tích VPC Flow Logs    | 28/10/2025   | 28/10/2025      | <https://000074.awsstudygroup.com/> |
| 4   | - Tìm hiểu Service Quotas: <br>&emsp; + Default vs applied quotas <br>&emsp; + Yêu cầu tăng quota <br>&emsp; + Quota alarms <br> - **Thực hành:** Xem và yêu cầu tăng quota                              | 29/10/2025   | 29/10/2025      | <https://000063.awsstudygroup.com/> |
| 5   | - Tìm hiểu Cost and Usage Management: <br>&emsp; + Resource usage với IAM <br>&emsp; + Cost allocation tags <br>&emsp; + Usage restrictions <br> - **Thực hành:** Triển khai cost management với IAM    | 30/10/2025   | 30/10/2025      | <https://000064.awsstudygroup.com/> |
| 6   | - Tìm hiểu EBS Data Lifecycle Manager: <br>&emsp; + Snapshot lifecycle policies <br>&emsp; + Automated archival <br>&emsp; + Retention policies <br> - **Thực hành:** Tự động hóa EBS snapshot archival | 31/10/2025   | 31/10/2025      | <https://000088.awsstudygroup.com/> |


### Kết quả đạt được tuần 8:

* Nắm vững Systems Manager Session Manager:
  * Kết nối tới EC2 instances không cần SSH keys hoặc bastion hosts
  * Cấu hình IAM policies cho Session Manager access
  * Bật session logging tới S3 và CloudWatch
  * Sử dụng Session Manager cho port forwarding
  * Hiểu lợi ích bảo mật so với SSH truyền thống

* Triển khai VPC Flow Logs cho network monitoring:
  * Bật VPC Flow Logs ở mức VPC, subnet, và ENI
  * Cấu hình log destinations (CloudWatch Logs, S3)
  * Phân tích network traffic patterns
  * Xác định security issues và troubleshoot connectivity
  * Tạo CloudWatch metrics từ flow logs

* Quản lý Service Quotas hiệu quả:
  * Hiểu default và applied quotas
  * Xem quotas trên các AWS services
  * Yêu cầu tăng quota khi cần
  * Thiết lập CloudWatch alarms cho quota monitoring
  * Lập kế hoạch capacity dựa trên quota limits

* Triển khai Resource Usage và Cost Management với IAM:
  * Tạo IAM policies để giới hạn resource usage theo region
  * Giới hạn EC2 instance families và sizes
  * Hạn chế EBS volume types để kiểm soát chi phí
  * Triển khai least privilege cho cost management
  * Xác nhận policy effectiveness

* Tự động hóa EBS Snapshots với Data Lifecycle Manager:
  * Tạo snapshot lifecycle policies
  * Cấu hình automated snapshot archival
  * Thiết lập retention rules cho compliance
  * Sử dụng single và multiple policy schedules
  * Đạt cost savings với snapshot archive tier


