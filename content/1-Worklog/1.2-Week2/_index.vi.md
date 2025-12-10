---
title: "Worklog Tuần 2"

weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Hiểu kiến thức nền tảng về mạng với Amazon VPC.
* Tìm hiểu dịch vụ compute cơ bản với Amazon EC2.
* Thực hành khởi tạo và quản lý EC2 instances.
* Hiểu IAM Roles cho EC2 instances.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Amazon VPC cơ bản: <br>&emsp; + VPC, Subnets (Public/Private) <br>&emsp; + Internet Gateway, NAT Gateway <br>&emsp; + Route Tables <br> - **Thực hành:** Tạo custom VPC                      | 15/09/2025   | 15/09/2025      | <https://000003.awsstudygroup.com/> |
| 3   | - Tìm hiểu VPC Security: <br>&emsp; + Security Groups <br>&emsp; + Network ACLs <br>&emsp; + VPC Flow Logs <br> - **Thực hành:** Cấu hình Security Groups và NACLs                                      | 16/09/2025   | 16/09/2025      | <https://000003.awsstudygroup.com/> |
| 4   | - Tìm hiểu Amazon EC2 cơ bản: <br>&emsp; + Instance types & families <br>&emsp; + Amazon Machine Images (AMI) <br>&emsp; + Instance lifecycle <br>&emsp; + Pricing options                              | 17/09/2025   | 17/09/2025      | <https://000004.awsstudygroup.com/> |
| 5   | - Tìm hiểu EC2 Storage & Networking: <br>&emsp; + EBS volumes & snapshots <br>&emsp; + Elastic IP <br>&emsp; + Key Pairs <br> - **Thực hành:** Khởi tạo EC2 instance & kết nối SSH                       | 18/09/2025   | 18/09/2025      | <https://000004.awsstudygroup.com/> |
| 6   | - Tìm hiểu IAM Roles cho EC2: <br>&emsp; + Instance profiles <br>&emsp; + Gán roles cho EC2 <br> - **Thực hành:** <br>&emsp; + Tạo IAM Role cho EC2 <br>&emsp; + Truy cập S3 từ EC2 bằng Role            | 19/09/2025   | 19/09/2025      | <https://000048.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* Nắm vững kiến thức mạng Amazon VPC:
  * Tạo custom VPC với CIDR block
  * Cấu hình Public và Private Subnets
  * Thiết lập Internet Gateway cho truy cập internet công cộng
  * Cấu hình Route Tables để định tuyến traffic
  * Hiểu NAT Gateway cho private subnet truy cập internet

* Triển khai bảo mật VPC:
  * Cấu hình Security Groups (stateful firewall)
  * Thiết lập Network ACLs (stateless firewall)
  * Hiểu các rules inbound/outbound

* Hiểu kiến thức cơ bản Amazon EC2:
  * Các loại instance types và use cases (t2, t3, m5, c5,...)
  * Lựa chọn và tạo AMI
  * Instance lifecycle: pending, running, stopping, terminated
  * Pricing: On-Demand, Reserved, Spot instances

* Thành công khởi tạo và quản lý EC2 instances:
  * Khởi tạo EC2 instance trong custom VPC
  * Kết nối vào instance qua SSH sử dụng Key Pair
  * Gắn và quản lý EBS volumes
  * Gán Elastic IP cho instance

* Cấu hình IAM Roles cho EC2:
  * Tạo IAM Role với policies phù hợp
  * Gắn Instance Profile vào EC2
  * Truy cập AWS services (S3) từ EC2 mà không cần hardcode credentials
  * Hiểu lợi ích bảo mật của IAM Roles so với Access Keys


