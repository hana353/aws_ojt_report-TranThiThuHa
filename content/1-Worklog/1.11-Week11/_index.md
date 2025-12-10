---
title: "Week 11 Worklog"

weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Learn threat detection with AWS GuardDuty.
* Understand automated patching with EC2 Image Builder.
* Master authentication with Amazon Cognito.
* Learn S3 Security Best Practices.
* Begin Reliability section with AWS Backup.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn AWS GuardDuty: <br>&emsp; + Threat detection <br>&emsp; + Finding types <br>&emsp; + Integration with EventBridge <br> - **Practice:** Enable GuardDuty and analyze findings               | 17/11/2025 | 17/11/2025      | <https://000098.awsstudygroup.com/> |
| Tue | - Learn EC2 Image Builder: <br>&emsp; + Image pipelines <br>&emsp; + Components and recipes <br>&emsp; + Automated patching <br> - **Practice:** Create automated AMI pipeline                     | 18/11/2025 | 18/11/2025      | <https://000099.awsstudygroup.com/> |
| Wed | - Learn Amazon Cognito: <br>&emsp; + User pools <br>&emsp; + Identity pools <br>&emsp; + Social identity providers <br> - **Practice:** Implement authentication for web app                       | 19/11/2025 | 19/11/2025      | <https://000141.awsstudygroup.com/> |
| Thu | - Learn S3 Security Best Practices: <br>&emsp; + Bucket policies <br>&emsp; + Access control lists <br>&emsp; + Encryption settings <br> - **Practice:** Secure S3 buckets                         | 20/11/2025 | 20/11/2025      | <https://000069.awsstudygroup.com/> |
| Fri | - Learn AWS Backup (Reliability): <br>&emsp; + Backup plans <br>&emsp; + Backup vaults <br>&emsp; + Cross-region backup <br> - **Practice:** Create backup plan for EC2 and RDS                    | 21/11/2025 | 21/11/2025      | <https://000013.awsstudygroup.com/> |


### Week 11 Achievements:

* Implemented AWS GuardDuty for threat detection:
  * Enabled GuardDuty in multiple regions
  * Analyzed different finding types (EC2, IAM, S3)
  * Configured EventBridge rules for alerts
  * Integrated with SNS for notifications
  * Understood threat intelligence sources

* Mastered EC2 Image Builder for automated patching:
  * Created image pipelines for AMI automation
  * Built components and recipes for configurations
  * Scheduled automated image builds
  * Implemented security hardening in images
  * Distributed AMIs across regions

* Implemented Amazon Cognito for authentication:
  * Created user pools for user management
  * Configured identity pools for AWS access
  * Integrated social identity providers (Google, Facebook)
  * Implemented MFA for enhanced security
  * Set up hosted UI for authentication flows

* Applied S3 Security Best Practices:
  * Configured bucket policies for access control
  * Enabled server-side encryption (SSE-S3, SSE-KMS)
  * Blocked public access at account level
  * Set up S3 Access Analyzer for monitoring
  * Implemented versioning and MFA delete

* Started Reliability section with AWS Backup:
  * Created backup plans with retention policies
  * Set up backup vaults with encryption
  * Configured cross-region backup for DR
  * Implemented backup for EC2, RDS, EFS
  * Set up lifecycle policies for cost optimization
