---
title: "Event 5"

weight: 1
chapter: false
pre: " <b> 4.5. </b> "
---

# Event Report: AWS Well-Architected Security Pillar Workshop

## Event Overview

**Event Name:** AWS Well-Architected Security Pillar Workshop

**Date & Time:** Saturday, November 29, 2025, 8:30 AM – 12:00 PM

**Location:** AWS Vietnam Office

**My Role:** Attendee

---

## Event Purpose

This morning workshop provided a comprehensive, in-depth exploration of the AWS Well-Architected Security Pillar, covering all five security domains: Identity & Access Management, Detection, Infrastructure Protection, Data Protection, and Incident Response.

The workshop was designed to equip participants with practical knowledge for implementing security best practices in AWS environments, featuring real-world examples from Vietnamese enterprises. The session emphasized that security is not a one-time implementation but a continuous journey requiring ongoing vigilance and improvement.

---

## Agenda Overview

### 8:30 – 8:50 AM | Opening & Security Foundation

**Security Pillar in Well-Architected Framework:**
- Understanding the role of Security Pillar within the Well-Architected Framework
- Core principles: Least Privilege, Zero Trust, Defense in Depth
- AWS Shared Responsibility Model and security boundaries
- Top cloud security threats in Vietnam's context

**Key Concepts:**
- **Least Privilege:** Granting only the minimum permissions necessary
- **Zero Trust:** Never trust, always verify approach
- **Defense in Depth:** Multiple layers of security controls
- **Shared Responsibility:** Understanding AWS vs. customer security responsibilities

### 8:50 – 9:30 AM | Pillar 1 – Identity & Access Management

**Modern IAM Architecture:**

**IAM Fundamentals:**
- Users, Roles, and Policies – avoiding long-term credentials
- Best practices for credential management
- Policy structure and evaluation logic

**IAM Identity Center:**
- Single Sign-On (SSO) capabilities
- Permission sets for centralized access management
- Multi-account access management

**Advanced IAM:**
- Service Control Policies (SCP) for multi-account environments
- Permission Boundaries for fine-grained access control
- Multi-Factor Authentication (MFA) implementation
- Credential rotation strategies
- IAM Access Analyzer for policy validation

**Mini Demo:** Validating IAM policies and simulating access scenarios

### 9:30 – 9:55 AM | Pillar 2 – Detection

**Detection & Continuous Monitoring:**

**AWS Security Services:**
- **CloudTrail:** Organization-level logging and audit trails
- **GuardDuty:** Intelligent threat detection service
- **Security Hub:** Centralized security findings and compliance

**Comprehensive Logging:**
- VPC Flow Logs for network traffic analysis
- Application Load Balancer (ALB) access logs
- S3 access logs and bucket logging
- Log aggregation and analysis strategies

**Alerting & Automation:**
- EventBridge for event-driven security automation
- Automated response to security events
- Integration with notification systems

**Detection-as-Code:**
- Infrastructure as Code for detection rules
- Version-controlled security configurations
- Automated deployment of detection mechanisms

### 9:55 – 10:10 AM | Break

Networking and refreshments.

### 10:10 – 10:40 AM | Pillar 3 – Infrastructure Protection

**Network & Workload Security:**

**VPC Security:**
- VPC segmentation strategies
- Private vs. public subnet placement
- Network isolation and segmentation best practices

**Network Security Controls:**
- **Security Groups:** Stateful firewall rules for EC2 instances
- **Network ACLs:** Stateless subnet-level filtering
- When to use Security Groups vs. NACLs
- Application patterns and use cases

**Application Protection:**
- **AWS WAF:** Web application firewall for application protection
- **AWS Shield:** DDoS protection service
- **Network Firewall:** Managed network firewall service
- Integration strategies for comprehensive protection

**Workload Security:**
- EC2 security best practices
- ECS security fundamentals
- EKS security basics
- Container security considerations

### 10:40 – 11:10 AM | Pillar 4 – Data Protection

**Encryption, Keys & Secrets:**

**AWS KMS (Key Management Service):**
- Key policies and access control
- Key grants for fine-grained permissions
- Key rotation strategies and automation
- Multi-region key management

**Encryption Implementation:**
- **Encryption at Rest:** S3, EBS, RDS, DynamoDB encryption
- **Encryption in Transit:** TLS/SSL implementation
- Encryption best practices for different services
- Performance considerations

**Secrets Management:**
- **AWS Secrets Manager:** Secure secret storage and rotation
- **Systems Manager Parameter Store:** Configuration and secrets management
- Rotation patterns and automation
- Integration with applications

**Data Classification & Access:**
- Data classification strategies
- Access guardrails based on data sensitivity
- Compliance and regulatory considerations

### 11:10 – 11:40 AM | Pillar 5 – Incident Response

**IR Playbook & Automation:**

**Incident Response Lifecycle:**
- Understanding the IR lifecycle according to AWS framework
- Preparation, detection, response, and recovery phases
- Continuous improvement and lessons learned

**Incident Response Playbooks:**

**Compromised IAM Key:**
- Detection and immediate response steps
- Key rotation and access revocation
- Investigation and remediation procedures

**S3 Public Exposure:**
- Identifying public bucket exposure
- Immediate remediation steps
- Access review and policy updates
- Prevention strategies

**EC2 Malware Detection:**
- Malware detection and identification
- Instance isolation procedures
- Evidence collection and analysis
- Remediation and recovery

**Automation:**
- Auto-response with Lambda functions
- Step Functions for orchestrated response
- Automated isolation and containment
- Evidence collection automation

### 11:40 – 12:00 PM | Wrap-up & Q&A

**Summary:**
- Recap of all five security pillars
- Interconnections between pillars
- Comprehensive security architecture approach

**Common Pitfalls:**
- Security mistakes common in Vietnamese enterprises
- Lessons learned from real-world scenarios
- Best practices to avoid common issues

**Learning Roadmap:**
- AWS Security Specialty certification path
- Solutions Architect Professional security focus
- Continuous learning resources
- Community engagement opportunities

---

## Key Highlights

### Comprehensive Security Framework

The AWS Well-Architected Security Pillar provides a complete framework covering all aspects of cloud security. The five pillars work together to create a defense-in-depth strategy that protects against various threats.

### Practical Implementation

The workshop focused on practical, actionable guidance rather than theoretical concepts. Real-world examples from Vietnamese enterprises made the content immediately applicable.

### Automation Focus

Throughout all pillars, automation was emphasized as essential for maintaining security at scale. Manual security processes are error-prone and don't scale effectively.

### Continuous Improvement

Security is presented as a continuous journey, not a destination. Regular reviews, updates, and improvements are essential for maintaining effective security posture.

---

## Key Learnings

### Strategic Insights

1. **Least Privilege is Foundation:**
   Always start with minimum permissions and expand only when necessary. This principle applies to all access control decisions.

2. **Zero Trust Architecture:**
   Never assume implicit trust, even within internal networks. Every access request should be verified and authorized.

3. **Defense in Depth:**
   Security requires multiple layers of controls. No single security measure is sufficient on its own.

4. **Automated Detection:**
   Detection capabilities must be automated and continuous. Manual monitoring cannot keep pace with modern threats.

5. **Incident Response Readiness:**
   Incident response playbooks must be documented, tested regularly, and updated based on lessons learned.

### Technical Insights

1. **IAM Best Practices:**
   - Avoid long-term credentials where possible
   - Use roles instead of users for applications
   - Implement MFA for all privileged access
   - Regularly review and rotate credentials

2. **Detection Strategy:**
   - Implement comprehensive logging at all layers
   - Use GuardDuty and Security Hub for centralized detection
   - Automate alerting and response mechanisms
   - Practice Detection-as-Code for consistency

3. **Infrastructure Protection:**
   - Proper VPC segmentation is critical
   - Understand when to use Security Groups vs. NACLs
   - Implement WAF and Shield for application protection
   - Secure workloads at every layer

4. **Data Protection:**
   - Encrypt data at rest and in transit
   - Use KMS for key management
   - Implement secrets rotation
   - Classify data and apply appropriate controls

5. **Incident Response:**
   - Prepare playbooks for common scenarios
   - Automate response where possible
   - Document and test procedures regularly
   - Learn from each incident

---

## Application to My Work

Based on the workshop insights, I plan to apply the following in my internship and future projects:

### Immediate Actions

1. **Implement IAM Access Analyzer:**
   - Use Access Analyzer to validate IAM policies in current projects
   - Identify and remediate overly permissive policies
   - Establish regular access reviews

2. **Set Up Security Monitoring:**
   - Enable GuardDuty for threat detection
   - Configure Security Hub for centralized findings
   - Set up CloudTrail organization-level logging

3. **Create Incident Response Playbooks:**
   - Document playbooks for common security scenarios
   - Test playbooks in practice exercises
   - Establish incident response procedures

4. **Review Security Groups:**
   - Audit Security Group rules using least privilege principle
   - Remove unnecessary open ports
   - Document security group purposes

5. **Enable Encryption:**
   - Enable encryption for all data stores (S3, RDS, DynamoDB)
   - Implement encryption in transit for all connections
   - Use KMS for key management

### Long-Term Strategies

1. **Security Maturity:**
   - Continuously improve security posture
   - Regular security reviews and audits
   - Implement security automation

2. **Skill Development:**
   - Pursue AWS Security Specialty certification
   - Deepen knowledge in each security pillar
   - Stay current with security best practices

3. **Security Culture:**
   - Promote security awareness
   - Integrate security into development workflows
   - Foster a security-first mindset

---

## Personal Experience

This workshop was extremely valuable for gaining comprehensive understanding of AWS security:

### Learning from Practical Demos

**Real-World Examples:**
The practical demos helped make abstract security concepts concrete and understandable. Seeing security configurations in action made the principles much clearer than reading documentation alone.

**Vietnamese Enterprise Context:**
Learning about common security pitfalls in Vietnamese enterprises was particularly insightful. Understanding local context helps identify relevant security concerns and solutions.

**Actionable Playbooks:**
The incident response playbooks provided templates that can be immediately applied. Having structured procedures for common scenarios is invaluable for effective incident response.

**Pillar Interconnections:**
Understanding how all five pillars work together helped me see security as a comprehensive system rather than isolated controls. This holistic view is essential for designing effective security architectures.

### Key Realizations

**Security is Continuous:**
The workshop reinforced that security is a continuous journey, not a destination. Regular reviews, updates, and improvements are essential.

**Automation is Essential:**
Automation emerged as a critical theme across all pillars. Manual security processes don't scale and are prone to errors.

**Framework Value:**
The Well-Architected Security Pillar provides a comprehensive framework that covers all aspects of cloud security systematically.

**Native AWS Tools:**
AWS provides powerful native tools for each security domain, making it possible to build comprehensive security without third-party solutions.

### Impact on My Career

This workshop has significantly expanded my understanding of cloud security and how to implement it effectively on AWS. The practical, hands-on approach provided immediately applicable knowledge. The workshop has inspired me to:

- Deepen my security expertise
- Pursue security certifications
- Contribute to building secure cloud architectures
- Stay current with evolving security threats and solutions

---

## Takeaways

### Strategic Principles

1. **Security is a Journey:**
   Security is a continuous process, not a one-time implementation. Regular reviews and improvements are essential.

2. **Automation is Key:**
   Automation is essential for maintaining security at scale. Manual processes are error-prone and don't scale effectively.

3. **Comprehensive Framework:**
   The Well-Architected Security Pillar provides a complete framework for cloud security covering all necessary domains.

4. **Regular Reviews:**
   Periodic security reviews and improvements are essential for maintaining effective security posture.

5. **Native Tools:**
   AWS provides powerful native tools for each security domain, enabling comprehensive security without third-party dependencies.

---

## Event Photos

*Add your event photos here*

---

> The AWS Well-Architected Security Pillar Workshop was a comprehensive and practical introduction to cloud security on AWS. The systematic coverage of all five security pillars, combined with practical demonstrations and real-world examples, provided a solid foundation for implementing security best practices. The workshop reinforced that security requires a holistic approach, with all pillars working together to create effective defense-in-depth. The insights gained from this workshop have equipped me with the knowledge and skills needed to design and implement secure cloud architectures, and have inspired me to continue developing my security expertise throughout my career.
