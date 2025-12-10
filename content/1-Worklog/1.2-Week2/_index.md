---
title: "Week 2 Worklog"

weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:

* Understand networking fundamentals with Amazon VPC.
* Learn compute essentials with Amazon EC2.
* Practice launching and managing EC2 instances.
* Understand IAM Roles for EC2 instances.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| Mon | - Learn Amazon VPC fundamentals: <br>&emsp; + VPC, Subnets (Public/Private) <br>&emsp; + Internet Gateway, NAT Gateway <br>&emsp; + Route Tables <br> - **Practice:** Create a custom VPC         | 15/09/2025 | 15/09/2025      | <https://000003.awsstudygroup.com/> |
| Tue | - Learn VPC Security: <br>&emsp; + Security Groups <br>&emsp; + Network ACLs <br>&emsp; + VPC Flow Logs <br> - **Practice:** Configure Security Groups and NACLs                                   | 16/09/2025 | 16/09/2025      | <https://000003.awsstudygroup.com/> |
| Wed | - Learn Amazon EC2 basics: <br>&emsp; + Instance types & families <br>&emsp; + Amazon Machine Images (AMI) <br>&emsp; + Instance lifecycle <br>&emsp; + Pricing options                           | 17/09/2025 | 17/09/2025      | <https://000004.awsstudygroup.com/> |
| Thu | - Learn EC2 Storage & Networking: <br>&emsp; + EBS volumes & snapshots <br>&emsp; + Elastic IP <br>&emsp; + Key Pairs <br> - **Practice:** Launch EC2 instance & connect via SSH                   | 18/09/2025 | 18/09/2025      | <https://000004.awsstudygroup.com/> |
| Fri | - Learn IAM Roles for EC2: <br>&emsp; + Instance profiles <br>&emsp; + Assigning roles to EC2 <br> - **Practice:** <br>&emsp; + Create IAM Role for EC2 <br>&emsp; + Access S3 from EC2 using Role | 19/09/2025 | 19/09/2025      | <https://000048.awsstudygroup.com/> |


### Week 2 Achievements:

* Mastered Amazon VPC networking concepts:
  * Created custom VPC with CIDR block
  * Configured Public and Private Subnets
  * Set up Internet Gateway for public internet access
  * Configured Route Tables for traffic routing
  * Understood NAT Gateway for private subnet internet access

* Implemented VPC security:
  * Configured Security Groups (stateful firewall)
  * Set up Network ACLs (stateless firewall)
  * Understood inbound/outbound rules

* Understood Amazon EC2 fundamentals:
  * Different instance types and use cases (t2, t3, m5, c5,...)
  * AMI selection and creation
  * Instance lifecycle: pending, running, stopping, terminated
  * Pricing: On-Demand, Reserved, Spot instances

* Successfully launched and managed EC2 instances:
  * Launched EC2 instance in custom VPC
  * Connected to instance via SSH using Key Pair
  * Attached and managed EBS volumes
  * Assigned Elastic IP to instance

* Configured IAM Roles for EC2:
  * Created IAM Role with appropriate policies
  * Attached Instance Profile to EC2
  * Accessed AWS services (S3) from EC2 without hardcoded credentials
  * Understood security benefits of using IAM Roles vs Access Keys
