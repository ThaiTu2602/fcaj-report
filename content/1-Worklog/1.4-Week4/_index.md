---
title: "Week 4 Worklog"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

* Learn how to set up Active Directory infrastructure in an AWS environment and configure secure remote management via Remote Desktop Gateway (RDGW).
* Explore hybrid domain name resolution concepts and prepare the environment for DNS integration.
* Study advanced firewall security mechanisms in VPC: **Security Group** and **Network ACLs**.
* Practice deploying multiple **Amazon EC2 Instances** at scale.
* Study and configure secure **Site-to-Site VPN** connectivity.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Deploy Hybrid DNS Infrastructure**<br>- Connect to Remote Desktop Gateway (RDGW)<br>- Deploy Microsoft Active Directory<br>- Verify Active Directory environment | 11/05/2026 | 11/05/2026 | ![Lab 10 Hybrid DNS] |
| 3 | **Study Security Groups** <br>- Understand the operating mechanism of Security Groups (Stateful Firewall) <br>- Configure Inbound and Outbound Rules <br>- Practice creating Security Groups for different application tiers | 12/05/2026 | 12/05/2026 | |
| 4 | **Study Network ACLs** <br>- Understand the operating mechanism of Network ACLs (Stateless Firewall) <br>- Compare differences between Security Groups and Network ACLs <br>- Configure Network ACLs for Subnets | 13/05/2026 | 13/05/2026 | |
| 5 | **Deploy Multiple EC2 Instances** <br>- Practice launching multiple EC2 Instances simultaneously <br>- Configure appropriate Security Groups for each Instance <br>- Test connectivity and communication between Instances | 14/05/2026 | 14/05/2026 | |
| 6 | **Configure Site-to-Site VPN** <br>- Study the architecture and operation of AWS Site-to-Site VPN <br>- Create Virtual Private Gateway and Customer Gateway <br>- Establish VPN tunnel connection <br>- Validate secure connectivity between on-premises environment and AWS | 15/05/2026 | 16/05/2026 | |

### Week 4 Achievements:

* **Built Active Directory Infrastructure and Secure Management**: Successfully deployed Microsoft Active Directory on AWS and established secure connectivity via Remote Desktop Gateway (RDGW). Managed identity configurations and validated the Active Directory environment for hybrid DNS models.
* **Mastered Security Group Mechanisms**: Clearly understood how Security Groups operate as a Stateful Firewall, learned how to configure Inbound/Outbound Rules to control traffic at the Instance level.
* **Deployed Network ACLs**: Configured Network ACLs as an additional security layer at the Subnet level, clearly understood the difference between Stateful (Security Group) and Stateless (Network ACLs) firewalls.
* **Deployed Multiple EC2 Instances at Scale**: Practiced launching and managing multiple EC2 Instances simultaneously, applying appropriate Security Groups for each application tier.
* **Configured Site-to-Site VPN Connectivity**: Successfully established secure VPN connectivity between the on-premises environment and AWS through Virtual Private Gateway and Customer Gateway, ensuring data encryption during transmission.
* **Strengthened Infrastructure Security Knowledge**: Accumulated practical experience in deploying multi-layer security for AWS network infrastructure, from Instance-level firewalls to Subnet-level ACLs and secure VPN connectivity.