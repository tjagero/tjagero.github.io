---
layout: single
permalink: /Projects/
title: " Projects"
---
## 📁 Projects

1. **Enforcing Least Privilege with IAM Permissions Boundaries in AWS**
2. **Designing and Deploying Virtual Networks in Microsoft Azure**
3. **Streamlining Network Resources to Ensure Instance Security**

---
### 1. 🔐 Enforcing Least Privilege with IAM Permissions Boundaries in AWS

<div style="margin-bottom: 30px;">
<img src="/assets/images/Least-Privilege.png" alt="least privilege image" width="1000px"/>
</div>

**Description:**  
In this hands-on project, I acted as a Cloud Security Engineer for a fictional startup, Mama Bear Catering & Pastry. My role involved setting up IAM users and enforcing the principle of least privilege using permissions boundaries in AWS.

**Objective:**  
Ensure system administrators had the appropriate level of access based on their roles, and restrict any unnecessary permissions to reduce security risks.

**Steps Taken:**
- Created three system administrator IAM users (`sysadmin-1`, `sysadmin-2`, and `sysadmin-3`)
- Created a `Sysadmins` IAM group with an AdministratorAccess policy
- Assigned EC2 permissions boundary to `sysadmin-2` and S3 permissions boundary to `sysadmin-3`
- Verified that users could only access services they were permitted to (e.g., `sysadmin-3` could not launch EC2 instances)

**Technologies Used:**  
`AWS IAM`, `IAM Permissions Boundaries`, `EC2`, `S3`, `AWS Console`, `Least Privilege Principle`

**Key Achievements:**  
- Demonstrated a practical use of IAM boundaries to enforce least privilege
- Successfully limited administrator capabilities by service
- Ensured security while maintaining role-based flexibility

**Link to full article:**  
[Read on Medium](https://medium.com/@jageroteddy/enforcing-least-privilege-with-iam-permissions-boundaries-in-aws-375d14757dec)

---
---

## Project 2: Securing Azure Virtual Networks through Network Segmentation

<div style="margin-bottom: 30px;">
<img src="/assets/images/virtual-network.png" alt="virtual network" width="1000px"/>
</div>

**Description:**
This project focused on designing and implementing secure virtual networking in Microsoft Azure to accommodate existing resources and support future scalability. Security was prioritized by segmenting networks appropriately, isolating resources using subnets, and restricting access through Network Security Groups (NSGs), effectively simulating a production-grade environment with secure interconnectivity.

---

**Tools & Technologies:** Microsoft Azure, Virtual Networks, Subnets, Azure VM, NSG, Public/Private IPs  

**Key Actions:**  
- Designed a segmented Azure VNet with public and private subnets  
- Deployed VMs and configured secure communication paths  
- Applied Network Security Groups (NSGs) to enforce traffic control policies  
- Ensured secure access to VMs using only allowed ports and sources  

**Results:**  
Enhanced security posture by minimizing exposure, enforcing least privilege access, and maintaining secure connectivity within the virtual environment.

**Detailed Documentation:** [See attached PDF]

---
---

## Project 3: Streamlining Network Resources to Ensure Instance Security 

<div style="margin-bottom: 30px;">
<img src="/assets/images/bastion.png" alt="bastion image" width="1000px"/>
</div>

### Overview

In this hands-on AWS networking project, I secured a private EC2 instance from public exposure while maintaining secure access to S3 and the internet. This involved creating a VPC Endpoint for S3 access and a NAT Gateway to allow internet access for updates, without exposing the instance publicly.



### Key Problem

- The private EC2 instance lacked internet access for updates and couldn't reach Amazon S3 securely.
- There was no VPC endpoint for S3 or NAT Gateway set up.
- This setup led to inefficient and insecure resource access within the VPC.



### Solution Implemented

- Created a **VPC Gateway Endpoint** for S3, allowing internal secure access without internet traversal.
- Created and configured a **NAT Gateway** to provide secure, outbound-only internet access.
- Updated route tables to reflect secure traffic flow.



### Tools & Services Used

- AWS VPC
- EC2 (Bastion and Private Instances)
- VPC Endpoints (S3)
- NAT Gateway
- Elastic IP
- Amazon CLI



### Key Benefits

- Secured the private EC2 instance while enabling essential internet connectivity.
- Enabled access to S3 via private AWS backbone.
- Reduced attack surface and followed best practices for network segmentation.




### Skills Demonstrated

- AWS Networking (VPC, Subnets, NAT Gateway)
- Security Best Practices
- EC2 Connectivity
- Infrastructure Design and Implementation

**Link to full article:**  
[Read on Medium](https://medium.com/@jageroteddy/streamlining-network-resources-to-ensure-instance-security-106b760f3cef)

---
---

