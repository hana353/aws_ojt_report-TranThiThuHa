---
title: "Worklog Tuần 10"

weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tìm hiểu bảo vệ ứng dụng với AWS WAF.
* Hiểu encryption với AWS KMS.
* Tìm hiểu bảo vệ dữ liệu với Amazon Macie.
* Nắm vững quản lý credentials với AWS Secrets Manager.
* Hiểu security governance với AWS Firewall Manager.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS WAF: <br>&emsp; + Web ACLs và rules <br>&emsp; + Managed rule groups <br>&emsp; + Rate-based rules <br> - **Thực hành:** Bảo vệ ALB/CloudFront với WAF                                    | 10/11/2025   | 10/11/2025      | <https://000026.awsstudygroup.com/> |
| 3   | - Tìm hiểu AWS KMS: <br>&emsp; + Customer managed keys <br>&emsp; + Key policies <br>&emsp; + Encryption context <br> - **Thực hành:** Encrypt S3 và EBS với KMS                                        | 11/11/2025   | 11/11/2025      | <https://000033.awsstudygroup.com/> |
| 4   | - Tìm hiểu Amazon Macie: <br>&emsp; + Data discovery <br>&emsp; + Sensitive data detection <br>&emsp; + Findings và alerts <br> - **Thực hành:** Quét S3 buckets để tìm sensitive data                  | 12/11/2025   | 12/11/2025      | <https://000090.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS Secrets Manager: <br>&emsp; + Secret storage <br>&emsp; + Automatic rotation <br>&emsp; + Cross-account access <br> - **Thực hành:** Lưu trữ và rotate database credentials              | 13/11/2025   | 13/11/2025      | <https://000096.awsstudygroup.com/> |
| 6   | - Tìm hiểu AWS Firewall Manager: <br>&emsp; + Security policies <br>&emsp; + Cross-account management <br>&emsp; + WAF rules deployment <br> - **Thực hành:** Deploy WAF rules across accounts          | 14/11/2025   | 14/11/2025      | <https://000097.awsstudygroup.com/> |


### Kết quả đạt được tuần 10:

* Triển khai AWS WAF cho application protection:
  * Tạo Web ACLs với custom và managed rules
  * Sử dụng AWS Managed Rules cho OWASP Top 10
  * Cấu hình rate-based rules cho DDoS mitigation
  * Liên kết WAF với ALB và CloudFront
  * Giám sát WAF metrics và sampled requests

* Nắm vững AWS KMS cho encryption:
  * Tạo customer managed keys (CMK)
  * Cấu hình key policies và IAM policies
  * Encrypt S3 buckets với SSE-KMS
  * Encrypt EBS volumes với KMS keys
  * Hiểu key rotation và auditing

* Triển khai Amazon Macie cho data protection:
  * Bật Macie cho S3 buckets
  * Cấu hình sensitive data discovery jobs
  * Phân tích findings cho PII và financial data
  * Thiết lập alerts cho sensitive data exposure
  * Tạo custom data identifiers

* Cấu hình AWS Secrets Manager:
  * Lưu trữ database credentials an toàn
  * Cấu hình automatic secret rotation
  * Truy xuất secrets từ Lambda functions
  * Triển khai cross-account secret access
  * Tích hợp với RDS cho automatic rotation

* Triển khai AWS Firewall Manager:
  * Tạo security policies cho WAF
  * Deploy rules across multiple accounts
  * Quản lý Security Groups tập trung
  * Cấu hình Shield Advanced policies
  * Giám sát compliance across organization


