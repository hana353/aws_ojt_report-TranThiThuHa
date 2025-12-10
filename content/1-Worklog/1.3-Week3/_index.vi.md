---
title: "Worklog Tuần 3"

weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Tìm hiểu môi trường phát triển đám mây với AWS Cloud9.
* Nắm vững dịch vụ lưu trữ đối tượng với Amazon S3.
* Host static website trên Amazon S3.
* Hiểu kiến thức cơ bản về database với Amazon RDS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS Cloud9: <br>&emsp; + Tính năng Cloud-based IDE <br>&emsp; + Thiết lập môi trường <br>&emsp; + Terminal tích hợp & debugging <br> - **Thực hành:** Tạo Cloud9 environment                 | 22/09/2025   | 22/09/2025      | <https://000049.awsstudygroup.com/> |
| 3   | - Tìm hiểu Amazon S3 cơ bản: <br>&emsp; + Buckets và Objects <br>&emsp; + Storage classes <br>&emsp; + Mô hình pricing S3 <br> - **Thực hành:** Tạo S3 bucket và upload objects                         | 23/09/2025   | 23/09/2025      | <https://000057.awsstudygroup.com/> |
| 4   | - Tìm hiểu S3 tính năng nâng cao: <br>&emsp; + Versioning <br>&emsp; + Lifecycle policies <br>&emsp; + Cross-Region Replication <br> - **Thực hành:** Cấu hình versioning và lifecycle rules            | 24/09/2025   | 24/09/2025      | <https://000057.awsstudygroup.com/> |
| 5   | - Tìm hiểu S3 Static Website Hosting: <br>&emsp; + Bật static hosting <br>&emsp; + Bucket policies cho public access <br>&emsp; + Custom error pages <br> - **Thực hành:** Deploy static website        | 25/09/2025   | 25/09/2025      | <https://000057.awsstudygroup.com/> |
| 6   | - Tìm hiểu Amazon RDS cơ bản: <br>&emsp; + Các database engines hỗ trợ <br>&emsp; + Multi-AZ deployments <br>&emsp; + Read Replicas <br> - **Thực hành:** Khởi tạo RDS MySQL instance                    | 26/09/2025   | 26/09/2025      | <https://000005.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:

* Nắm vững môi trường phát triển AWS Cloud9:
  * Tạo và cấu hình Cloud9 environment
  * Sử dụng terminal tích hợp cho AWS CLI commands
  * Phát triển và test code trực tiếp trên cloud
  * Hiểu tính năng collaboration cho pair programming

* Hiểu dịch vụ lưu trữ đối tượng Amazon S3:
  * Tạo S3 buckets với naming conventions phù hợp
  * Upload, download, và quản lý objects
  * Hiểu các storage classes: Standard, IA, Glacier,...
  * Cấu hình bucket policies và ACLs

* Triển khai các tính năng nâng cao của S3:
  * Bật versioning để bảo vệ khỏi xóa nhầm
  * Tạo lifecycle policies để tối ưu chi phí
  * Hiểu Cross-Region Replication cho disaster recovery

* Thành công host static website trên S3:
  * Bật static website hosting trên bucket
  * Cấu hình bucket policy cho public read access
  * Thiết lập index và error documents
  * Deploy website HTML/CSS/JS

* Tìm hiểu kiến thức cơ bản Amazon RDS:
  * Hiểu lợi ích của managed database service
  * Khởi tạo RDS MySQL instance trong VPC
  * Cấu hình security groups cho database access
  * Kết nối tới RDS từ EC2 instance
  * Hiểu Multi-AZ cho high availability


