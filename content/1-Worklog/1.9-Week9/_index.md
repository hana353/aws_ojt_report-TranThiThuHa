---
title: "Week 9 Worklog"
date: "`r Sys.Date()`"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Learn identity federation with AWS Single Sign-On.
* Understand IAM Permission Boundaries.
* Master access control with IAM Policies and Conditions.
* Learn security compliance with AWS Security Hub.
* Understand private connectivity with VPC Endpoints.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn AWS Single Sign-On: <br>&emsp; + Identity federation <br>&emsp; + SSO for Organizations <br>&emsp; + Permission sets <br> - **Practice:** Set up SSO for AWS Organization                  | 03/11/2025 | 03/11/2025      | <https://000012.awsstudygroup.com/> |
| Tue | - Learn IAM Permission Boundaries: <br>&emsp; + Boundary concepts <br>&emsp; + Delegating permissions <br>&emsp; + Use cases <br> - **Practice:** Limit user permissions with boundaries           | 04/11/2025 | 04/11/2025      | <https://000030.awsstudygroup.com/> |
| Wed | - Learn IAM Policies and Conditions: <br>&emsp; + Policy conditions <br>&emsp; + Role switching limits <br>&emsp; + Context keys <br> - **Practice:** Implement conditional role switching          | 05/11/2025 | 05/11/2025      | <https://000044.awsstudygroup.com/> |
| Thu | - Learn AWS Security Hub: <br>&emsp; + Security standards <br>&emsp; + Findings aggregation <br>&emsp; + Compliance checks <br> - **Practice:** Enable Security Hub and review compliance           | 06/11/2025 | 06/11/2025      | <https://000018.awsstudygroup.com/> |
| Fri | - Learn VPC Endpoints: <br>&emsp; + Gateway vs Interface endpoints <br>&emsp; + Private S3 access <br>&emsp; + Endpoint policies <br> - **Practice:** Set up private S3 access via VPC Endpoint     | 07/11/2025 | 07/11/2025      | <https://000111.awsstudygroup.com/> |


### Week 9 Achievements:

* Implemented AWS Single Sign-On:
  * Set up SSO for AWS Organizations
  * Configured identity sources (AWS SSO, AD, external IdP)
  * Created permission sets for different roles
  * Enabled SSO access to multiple AWS accounts
  * Understood federation and SAML integration

* Mastered IAM Permission Boundaries:
  * Understood permission boundary concepts
  * Created boundaries to limit maximum permissions
  * Delegated user creation safely to developers
  * Prevented privilege escalation
  * Combined with service control policies

* Implemented IAM Policies and Conditions:
  * Used condition keys in IAM policies
  * Implemented time-based access restrictions
  * Limited role switching with conditions
  * Used resource tags for access control
  * Created fine-grained access policies

* Configured AWS Security Hub for compliance:
  * Enabled AWS Foundational Security Best Practices
  * Reviewed CIS AWS Foundations Benchmark
  * Aggregated findings from GuardDuty, Inspector, Macie
  * Set up automated remediation workflows
  * Created custom security insights

* Configured VPC Endpoints for private access:
  * Created Gateway Endpoint for S3
  * Created Interface Endpoints for other AWS services
  * Configured endpoint policies for access control
  * Enabled private DNS for seamless integration
  * Eliminated need for NAT Gateway for AWS services
