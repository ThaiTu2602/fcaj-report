---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Learn and study foundational knowledge of Cloud networking with **Amazon VPC**.
* Initialize, configure, and understand the operational mechanisms of virtual servers using **Amazon EC2**.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Explore Amazon VPC Architecture** <br>- Study core concepts: VPC, Subnet, CIDR Block <br>- Differentiate between Public Subnet and Private Subnet <br>- Learn about Internet Gateway and Route Table | 04/05/2026 | 04/05/2026 | |
| 3 | **Hands-on VPC Creation** <br>- Create a VPC with appropriate CIDR configuration <br>- Create Public Subnet and Private Subnet <br>- Create and attach Internet Gateway to the VPC <br>- Configure Route Tables for Subnets | 05/05/2026 | 05/05/2026 | |
| 4 | **Explore Amazon EC2** <br>- Study Instance Types (t2, t3, m5, ...) <br>- Learn about Amazon Machine Image (AMI) <br>- Understand Elastic Block Store (EBS) and volume types | 06/05/2026 | 06/05/2026 | |
| 5 | **Hands-on EC2 Initialization** <br>- Create Security Group for EC2 Instance <br>- Launch EC2 Instance in Public Subnet <br>- Configure Key Pair and SSH connection to Instance | 07/05/2026 | 07/05/2026 | |
| 6 | **Advanced Networking Configuration for EC2** <br>- Launch EC2 Instance in Private Subnet <br>- Allocate Elastic IP <br>- Create NAT Gateway to enable Private Instance internet access <br>- Validate connectivity between Public and Private EC2 | 08/05/2026 | 09/05/2026 | |

### Week 3 Achievements:

* **Mastered Amazon VPC Network Architecture**: Clearly understood the core components of VPC including Subnet, CIDR Block, Internet Gateway, and Route Table, along with their roles in building a secure Cloud network infrastructure.
* **Designed Multi-Tier VPC Network**: Successfully built a VPC architecture with Public Subnet and Private Subnet, separating resources by access levels to enhance security.
* **Deployed Amazon EC2 Virtual Servers**: Initialized and configured EC2 Instances with appropriate Instance Types, AMIs, and EBS volumes, understanding the operational process of virtual servers on the Cloud.
* **Configured Secure Connectivity**: Set up Security Groups, Key Pairs, and SSH connections to securely manage EC2 Instances remotely.
* **Deployed NAT Gateway**: Configured NAT Gateway and Elastic IP to enable EC2 Instances in Private Subnet to access the outbound Internet without exposing them to inbound Internet traffic.
* **Validated End-to-End Connectivity**: Successfully tested communication between EC2 Instances in Public and Private Subnets, ensuring network traffic flow operated as designed.