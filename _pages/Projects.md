---
layout: single
permalink: /Projects/
title: "Projects"
---

## 📁 Projects

### 🔐 Enforcing Least Privilege with IAM Permissions Boundaries in AWS

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
