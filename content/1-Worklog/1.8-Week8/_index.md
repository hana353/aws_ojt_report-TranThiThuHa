---
title: "Week 8 Worklog"

weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* Learn remote server access with Systems Manager Session Manager.
* Master network monitoring with VPC Flow Logs.
* Understand service quotas management.
* Learn cost and usage management on AWS.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn Session Manager: <br>&emsp; + Secure shell access without SSH <br>&emsp; + IAM policies for Session Manager <br>&emsp; + Logging and auditing <br> - **Practice:** Connect to EC2 via Session Manager | 27/10/2025 | 27/10/2025      | <https://000058.awsstudygroup.com/> |
| Tue | - Learn VPC Flow Logs: <br>&emsp; + Flow log concepts <br>&emsp; + Log destinations (S3, CloudWatch) <br>&emsp; + Analyzing network traffic <br> - **Practice:** Enable and analyze VPC Flow Logs | 28/10/2025 | 28/10/2025      | <https://000074.awsstudygroup.com/> |
| Wed | - Learn Service Quotas: <br>&emsp; + Default vs applied quotas <br>&emsp; + Requesting quota increases <br>&emsp; + Quota alarms <br> - **Practice:** View and request quota increases            | 29/10/2025 | 29/10/2025      | <https://000063.awsstudygroup.com/> |
| Thu | - Learn Cost and Usage Management: <br>&emsp; + Resource usage with IAM <br>&emsp; + Cost allocation tags <br>&emsp; + Usage restrictions <br> - **Practice:** Implement cost management with IAM  | 30/10/2025 | 30/10/2025      | <https://000064.awsstudygroup.com/> |
| Fri | - Learn EBS Data Lifecycle Manager: <br>&emsp; + Snapshot lifecycle policies <br>&emsp; + Automated archival <br>&emsp; + Retention policies <br> - **Practice:** Automate EBS snapshot archival    | 31/10/2025 | 31/10/2025      | <https://000088.awsstudygroup.com/> |


### Week 8 Achievements:

* Mastered Systems Manager Session Manager:
  * Connected to EC2 instances without SSH keys or bastion hosts
  * Configured IAM policies for Session Manager access
  * Enabled session logging to S3 and CloudWatch
  * Used Session Manager for port forwarding
  * Understood security benefits over traditional SSH

* Implemented VPC Flow Logs for network monitoring:
  * Enabled VPC Flow Logs at VPC, subnet, and ENI levels
  * Configured log destinations (CloudWatch Logs, S3)
  * Analyzed network traffic patterns
  * Identified security issues and troubleshot connectivity
  * Created CloudWatch metrics from flow logs

* Managed Service Quotas effectively:
  * Understood default and applied quotas
  * Viewed quotas across AWS services
  * Requested quota increases when needed
  * Set up CloudWatch alarms for quota monitoring
  * Planned capacity based on quota limits

* Implemented Resource Usage and Cost Management with IAM:
  * Created IAM policies to limit resource usage by region
  * Restricted EC2 instance families and sizes
  * Limited EBS volume types for cost control
  * Implemented least privilege for cost management
  * Validated policy effectiveness

* Automated EBS Snapshots with Data Lifecycle Manager:
  * Created snapshot lifecycle policies
  * Configured automated snapshot archival
  * Set up retention rules for compliance
  * Used single and multiple policy schedules
  * Achieved cost savings with snapshot archive tier
