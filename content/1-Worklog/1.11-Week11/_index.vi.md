---
title: "Worklog Tuần 11"
date: "`r Sys.Date()`"
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Tìm hiểu threat detection với AWS GuardDuty.
* Hiểu automated patching với EC2 Image Builder.
* Nắm vững authentication với Amazon Cognito.
* Tìm hiểu S3 Security Best Practices.
* Bắt đầu phần Reliability với AWS Backup.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS GuardDuty: <br>&emsp; + Threat detection <br>&emsp; + Finding types <br>&emsp; + Integration với EventBridge <br> - **Thực hành:** Bật GuardDuty và phân tích findings                   | 17/11/2025   | 17/11/2025      | <https://000098.awsstudygroup.com/> |
| 3   | - Tìm hiểu EC2 Image Builder: <br>&emsp; + Image pipelines <br>&emsp; + Components và recipes <br>&emsp; + Automated patching <br> - **Thực hành:** Tạo automated AMI pipeline                          | 18/11/2025   | 18/11/2025      | <https://000099.awsstudygroup.com/> |
| 4   | - Tìm hiểu Amazon Cognito: <br>&emsp; + User pools <br>&emsp; + Identity pools <br>&emsp; + Social identity providers <br> - **Thực hành:** Triển khai authentication cho web app                       | 19/11/2025   | 19/11/2025      | <https://000141.awsstudygroup.com/> |
| 5   | - Tìm hiểu S3 Security Best Practices: <br>&emsp; + Bucket policies <br>&emsp; + Access control lists <br>&emsp; + Encryption settings <br> - **Thực hành:** Bảo mật S3 buckets                         | 20/11/2025   | 20/11/2025      | <https://000069.awsstudygroup.com/> |
| 6   | - Tìm hiểu AWS Backup (Reliability): <br>&emsp; + Backup plans <br>&emsp; + Backup vaults <br>&emsp; + Cross-region backup <br> - **Thực hành:** Tạo backup plan cho EC2 và RDS                         | 21/11/2025   | 21/11/2025      | <https://000013.awsstudygroup.com/> |


### Kết quả đạt được tuần 11:

* Triển khai AWS GuardDuty cho threat detection:
  * Bật GuardDuty ở nhiều regions
  * Phân tích các finding types (EC2, IAM, S3)
  * Cấu hình EventBridge rules cho alerts
  * Tích hợp với SNS cho notifications
  * Hiểu threat intelligence sources

* Nắm vững EC2 Image Builder cho automated patching:
  * Tạo image pipelines cho AMI automation
  * Xây dựng components và recipes cho configurations
  * Lên lịch automated image builds
  * Triển khai security hardening trong images
  * Phân phối AMIs across regions

* Triển khai Amazon Cognito cho authentication:
  * Tạo user pools cho user management
  * Cấu hình identity pools cho AWS access
  * Tích hợp social identity providers (Google, Facebook)
  * Triển khai MFA cho enhanced security
  * Thiết lập hosted UI cho authentication flows

* Áp dụng S3 Security Best Practices:
  * Cấu hình bucket policies cho access control
  * Bật server-side encryption (SSE-S3, SSE-KMS)
  * Block public access ở account level
  * Thiết lập S3 Access Analyzer cho monitoring
  * Triển khai versioning và MFA delete

* Bắt đầu phần Reliability với AWS Backup:
  * Tạo backup plans với retention policies
  * Thiết lập backup vaults với encryption
  * Cấu hình cross-region backup cho DR
  * Triển khai backup cho EC2, RDS, EFS
  * Thiết lập lifecycle policies cho cost optimization


