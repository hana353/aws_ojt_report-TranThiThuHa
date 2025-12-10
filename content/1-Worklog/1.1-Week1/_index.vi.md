---
title: "Worklog Tuần 1"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


### Mục tiêu tuần 1:

* Làm quen với môi trường thực tập và các thành viên trong First Cloud Journey.
* Hiểu tổng quan về AWS và các dịch vụ cơ bản.
* Tạo tài khoản AWS và thiết lập quản lý chi phí.
* Nắm vững AWS IAM để quản lý truy cập và bảo mật.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Làm quen với các thành viên FCJ <br> - Đọc và lưu ý các nội quy, quy định tại đơn vị thực tập <br> - Giới thiệu về lộ trình học Cloud Engineer                                                        | 08/09/2025   | 08/09/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu tổng quan về AWS <br>&emsp; + AWS là gì? <br>&emsp; + Các nhóm dịch vụ chính <br>&emsp; + Mô hình trách nhiệm chung <br> - Tạo tài khoản AWS Free Tier                                       | 09/09/2025   | 09/09/2025      | <https://000001.awsstudygroup.com/> |
| 4   | - Tìm hiểu AWS Budgets và quản lý chi phí <br> - **Thực hành:** <br>&emsp; + Thiết lập AWS Budgets <br>&emsp; + Cấu hình cảnh báo chi phí <br>&emsp; + Sử dụng Cost Explorer                            | 10/09/2025   | 10/09/2025      | <https://000007.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS IAM: <br>&emsp; + Users, Groups, Roles <br>&emsp; + Policies và Permissions <br>&emsp; + Best practices bảo mật <br> - **Thực hành:** Tạo IAM User, Group và gán Policies                | 11/09/2025   | 11/09/2025      | <https://000002.awsstudygroup.com/> |
| 6   | - Tìm hiểu AWS Console & AWS CLI <br> - **Thực hành:** <br>&emsp; + Cài đặt và cấu hình AWS CLI <br>&emsp; + Sử dụng CLI với IAM credentials <br>&emsp; + Thao tác cơ bản với CLI                       | 12/09/2025   | 12/09/2025      | <https://000011.awsstudygroup.com/> |


### Kết quả đạt được tuần 1:

* Hoàn thành việc làm quen với môi trường thực tập và nắm được quy trình làm việc tại FCJ.

* Hiểu tổng quan về AWS:
  * AWS là nền tảng đám mây hàng đầu với hơn 200 dịch vụ
  * Các nhóm dịch vụ chính: Compute, Storage, Database, Networking, Security,...
  * Mô hình trách nhiệm chung (Shared Responsibility Model)
  * Các AWS Region và Availability Zone

* Đã tạo và kích hoạt thành công tài khoản AWS Free Tier.

* Thiết lập quản lý chi phí với AWS Budgets:
  * Tạo budget với ngưỡng cảnh báo
  * Cấu hình thông báo qua email khi chi phí vượt ngưỡng
  * Sử dụng Cost Explorer để theo dõi chi tiêu

* Nắm vững AWS IAM và đã thực hành:
  * Tạo IAM User với quyền truy cập programmatic
  * Tạo IAM Group và gán Users vào Group
  * Thiết lập IAM Policies để quản lý quyền truy cập
  * Bật MFA cho tài khoản root và IAM User

* Cài đặt và cấu hình AWS CLI thành công:
  * Cài đặt AWS CLI v2 trên máy tính
  * Cấu hình credentials với Access Key và Secret Key
  * Thiết lập default region
  * Thực hiện các lệnh cơ bản: `aws sts get-caller-identity`, `aws iam list-users`,...

* Biết cách sử dụng song song AWS Console (giao diện web) và AWS CLI để quản lý tài nguyên.


