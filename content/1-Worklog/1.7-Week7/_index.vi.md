---
title: "Worklog Tuần 7"

weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Tìm hiểu Infrastructure as Code với AWS CloudFormation.
* Nắm vững AWS CDK cơ bản và nâng cao.
* Hiểu EC2 resource optimization và right-sizing.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                              | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS CloudFormation: <br>&emsp; + Templates (YAML/JSON) <br>&emsp; + Stacks và StackSets <br>&emsp; + Intrinsic functions <br> - **Thực hành:** Tạo VPC stack với CloudFormation              | 20/10/2025   | 20/10/2025      | <https://000037.awsstudygroup.com/> |
| 3   | - Tìm hiểu CloudFormation nâng cao: <br>&emsp; + Nested stacks <br>&emsp; + Change sets <br>&emsp; + Drift detection <br> - **Thực hành:** Deploy multi-tier application với CloudFormation             | 21/10/2025   | 21/10/2025      | <https://000037.awsstudygroup.com/> |
| 4   | - Tìm hiểu AWS CDK: <br>&emsp; + CDK concepts và constructs <br>&emsp; + CDK vs CloudFormation <br>&emsp; + Supported languages <br> - **Thực hành:** Tạo infrastructure với CDK TypeScript              | 22/10/2025   | 22/10/2025      | <https://000038.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS CDK Advanced: <br>&emsp; + Custom constructs <br>&emsp; + CDK Pipelines <br>&emsp; + Testing CDK apps <br> - **Thực hành:** Xây dựng CI/CD pipeline với CDK Pipelines                     | 23/10/2025   | 23/10/2025      | <https://000076.awsstudygroup.com/> |
| 6   | - Tìm hiểu EC2 Right-Sizing: <br>&emsp; + Khái niệm resource optimization <br>&emsp; + AWS Compute Optimizer <br>&emsp; + Chiến lược tiết kiệm chi phí <br> - **Thực hành:** Phân tích và right-size EC2  | 24/10/2025   | 24/10/2025      | <https://000032.awsstudygroup.com/> |


### Kết quả đạt được tuần 7:

* Nắm vững AWS CloudFormation cho Infrastructure as Code:
  * Tạo CloudFormation templates bằng YAML/JSON
  * Deploy và quản lý stacks cho VPC, EC2, RDS
  * Sử dụng intrinsic functions (Ref, Fn::GetAtt, Fn::Join)
  * Triển khai nested stacks cho modularity
  * Sử dụng change sets cho safe updates
  * Phát hiện và remediate configuration drift

* Tìm hiểu AWS CDK cho cloud development:
  * Hiểu CDK constructs (L1, L2, L3)
  * Tạo infrastructure sử dụng TypeScript/Python
  * Synthesize CloudFormation templates từ CDK
  * Deploy stacks với cdk deploy
  * Sử dụng CDK patterns cho best practices

* Nắm vững AWS CDK Advanced:
  * Tạo custom L2 và L3 constructs
  * Xây dựng CI/CD pipelines với CDK Pipelines
  * Triển khai unit tests cho CDK apps
  * Sử dụng CDK aspects cho compliance
  * Deploy multi-stage applications

* Triển khai EC2 Right-Sizing để tối ưu chi phí:
  * Sử dụng AWS Compute Optimizer cho recommendations
  * Phân tích EC2 instance utilization metrics
  * Xác định instances over-provisioned và under-utilized
  * Resize instances phù hợp với workload requirements
  * Đạt được cost savings thông qua right-sizing


