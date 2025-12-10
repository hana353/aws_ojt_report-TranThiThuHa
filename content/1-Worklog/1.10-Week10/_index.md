---
title: "Week 10 Worklog"
date: "`r Sys.Date()`"
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Learn application protection with AWS WAF.
* Understand encryption with AWS KMS.
* Learn data protection with Amazon Macie.
* Master credentials management with AWS Secrets Manager.
* Understand security governance with AWS Firewall Manager.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn AWS WAF: <br>&emsp; + Web ACLs and rules <br>&emsp; + Managed rule groups <br>&emsp; + Rate-based rules <br> - **Practice:** Protect ALB/CloudFront with WAF                               | 10/11/2025 | 10/11/2025      | <https://000026.awsstudygroup.com/> |
| Tue | - Learn AWS KMS: <br>&emsp; + Customer managed keys <br>&emsp; + Key policies <br>&emsp; + Encryption context <br> - **Practice:** Encrypt S3 and EBS with KMS                                     | 11/11/2025 | 11/11/2025      | <https://000033.awsstudygroup.com/> |
| Wed | - Learn Amazon Macie: <br>&emsp; + Data discovery <br>&emsp; + Sensitive data detection <br>&emsp; + Findings and alerts <br> - **Practice:** Scan S3 buckets for sensitive data                   | 12/11/2025 | 12/11/2025      | <https://000090.awsstudygroup.com/> |
| Thu | - Learn AWS Secrets Manager: <br>&emsp; + Secret storage <br>&emsp; + Automatic rotation <br>&emsp; + Cross-account access <br> - **Practice:** Store and rotate database credentials              | 13/11/2025 | 13/11/2025      | <https://000096.awsstudygroup.com/> |
| Fri | - Learn AWS Firewall Manager: <br>&emsp; + Security policies <br>&emsp; + Cross-account management <br>&emsp; + WAF rules deployment <br> - **Practice:** Deploy WAF rules across accounts         | 14/11/2025 | 14/11/2025      | <https://000097.awsstudygroup.com/> |


### Week 10 Achievements:

* Implemented AWS WAF for application protection:
  * Created Web ACLs with custom and managed rules
  * Used AWS Managed Rules for OWASP Top 10
  * Configured rate-based rules for DDoS mitigation
  * Associated WAF with ALB and CloudFront
  * Monitored WAF metrics and sampled requests

* Mastered AWS KMS for encryption:
  * Created customer managed keys (CMK)
  * Configured key policies and IAM policies
  * Encrypted S3 buckets with SSE-KMS
  * Encrypted EBS volumes with KMS keys
  * Understood key rotation and auditing

* Implemented Amazon Macie for data protection:
  * Enabled Macie for S3 buckets
  * Configured sensitive data discovery jobs
  * Analyzed findings for PII and financial data
  * Set up alerts for sensitive data exposure
  * Created custom data identifiers

* Configured AWS Secrets Manager:
  * Stored database credentials securely
  * Configured automatic secret rotation
  * Retrieved secrets from Lambda functions
  * Implemented cross-account secret access
  * Integrated with RDS for automatic rotation

* Implemented AWS Firewall Manager:
  * Created security policies for WAF
  * Deployed rules across multiple accounts
  * Managed Security Groups centrally
  * Configured Shield Advanced policies
  * Monitored compliance across organization
