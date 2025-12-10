---
title: "Worklog Tuần 9"

weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Tìm hiểu identity federation với AWS Single Sign-On.
* Hiểu IAM Permission Boundaries.
* Nắm vững access control với IAM Policies và Conditions.
* Tìm hiểu security compliance với AWS Security Hub.
* Hiểu private connectivity với VPC Endpoints.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS Single Sign-On: <br>&emsp; + Identity federation <br>&emsp; + SSO cho Organizations <br>&emsp; + Permission sets <br> - **Thực hành:** Thiết lập SSO cho AWS Organization                | 03/11/2025   | 03/11/2025      | <https://000012.awsstudygroup.com/> |
| 3   | - Tìm hiểu IAM Permission Boundaries: <br>&emsp; + Boundary concepts <br>&emsp; + Delegating permissions <br>&emsp; + Use cases <br> - **Thực hành:** Giới hạn user permissions với boundaries          | 04/11/2025   | 04/11/2025      | <https://000030.awsstudygroup.com/> |
| 4   | - Tìm hiểu IAM Policies và Conditions: <br>&emsp; + Policy conditions <br>&emsp; + Role switching limits <br>&emsp; + Context keys <br> - **Thực hành:** Triển khai conditional role switching          | 05/11/2025   | 05/11/2025      | <https://000044.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS Security Hub: <br>&emsp; + Security standards <br>&emsp; + Findings aggregation <br>&emsp; + Compliance checks <br> - **Thực hành:** Bật Security Hub và review compliance               | 06/11/2025   | 06/11/2025      | <https://000018.awsstudygroup.com/> |
| 6   | - Tìm hiểu VPC Endpoints: <br>&emsp; + Gateway vs Interface endpoints <br>&emsp; + Private S3 access <br>&emsp; + Endpoint policies <br> - **Thực hành:** Thiết lập private S3 access qua VPC Endpoint  | 07/11/2025   | 07/11/2025      | <https://000111.awsstudygroup.com/> |


### Kết quả đạt được tuần 9:

* Triển khai AWS Single Sign-On:
  * Thiết lập SSO cho AWS Organizations
  * Cấu hình identity sources (AWS SSO, AD, external IdP)
  * Tạo permission sets cho các roles khác nhau
  * Bật SSO access cho nhiều AWS accounts
  * Hiểu federation và SAML integration

* Nắm vững IAM Permission Boundaries:
  * Hiểu permission boundary concepts
  * Tạo boundaries để giới hạn maximum permissions
  * Delegate user creation an toàn cho developers
  * Ngăn chặn privilege escalation
  * Kết hợp với service control policies

* Triển khai IAM Policies và Conditions:
  * Sử dụng condition keys trong IAM policies
  * Triển khai time-based access restrictions
  * Giới hạn role switching với conditions
  * Sử dụng resource tags cho access control
  * Tạo fine-grained access policies

* Cấu hình AWS Security Hub cho compliance:
  * Bật AWS Foundational Security Best Practices
  * Review CIS AWS Foundations Benchmark
  * Aggregate findings từ GuardDuty, Inspector, Macie
  * Thiết lập automated remediation workflows
  * Tạo custom security insights

* Cấu hình VPC Endpoints cho private access:
  * Tạo Gateway Endpoint cho S3
  * Tạo Interface Endpoints cho các AWS services khác
  * Cấu hình endpoint policies để access control
  * Bật private DNS cho seamless integration
  * Loại bỏ nhu cầu NAT Gateway cho AWS services


