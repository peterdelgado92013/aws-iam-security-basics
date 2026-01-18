# 🔐 AWS IAM Security & Least Privilege Project

![AWS IAM Security Header](assets/IAM-Header.png)

---

## 📄 Project Summary

This project demonstrates hands-on experience implementing **AWS Identity and Access Management (IAM)** security controls to protect cloud resources. The primary focus is applying the **principle of least privilege**, securing access to **Amazon EC2**, and validating permissions through real-world testing.

Instead of relying on assumptions, permissions were verified by logging in as an IAM user and attempting both allowed and denied actions against **production** and **development** EC2 environments.

---

## 🎯 Project Objectives

- Secure AWS resources using IAM best practices  
- Prevent over-permissioned users  
- Separate production and development access  
- Validate permissions through real user testing  

---

## 🛠️ Tools & Technologies Used

- **AWS Identity and Access Management (IAM)**
- **Amazon EC2**
- **IAM Policy JSON**
- **AWS Management Console**
- **EC2 Tagging (environment-based access control)**
- **Git & GitHub**

---

## 📸 Project Walkthrough (Screenshots)

### 1) Launch EC2 Instance
![Launch EC2](screenshots/01-Launch-EC2-Instance.png)

---

### 2) Apply EC2 Tags
![EC2 Tags](screenshots/02-EC2-Instance-Tags.png)

---

### 3) Review IAM Policy (JSON)
![IAM Policy JSON](screenshots/03-EC2-Policies-JSON.png)

---

### 4) View Account Alias
![Account Alias](screenshots/04-Account-Alias.png)

---

### 5) Create Account Alias
![Create Account Alias](screenshots/05-Creat-Account-Alias.png)

---

### 6) Create IAM User
![Create User](screenshots/06-Create-User.png)

---

### 7) Test User Permissions
![Permissions Test](screenshots/07-user-account-permissions-test.png)

---

### 8) Attempt to Stop Production Instance (Denied)
![Stop Prod Test](screenshots/08-user-account-stop-prod-instance-test.png)

---

### 9) Stop Development Instance (Allowed)
![Stop Dev Test](screenshots/09-user-account-stop-development-instance-test.png)

---

## 🧠 Skills & Concepts Learned

- Creating and managing IAM users securely  
- Applying the **principle of least privilege**  
- Reading and understanding IAM policy JSON  
- Differentiating access between production and development environments  
- Testing permissions by simulating real user behavior  
- Understanding how IAM affects EC2 operational security  
- Documenting cloud projects for professional portfolios  

---

## 🔐 Security Best Practices Applied

- Avoided use of the root account for daily operations  
- Scoped permissions to only required EC2 actions  
- Prevented unauthorized modification of production resources  
- Used environment tagging to support access control decisions  
- Verified access through live permission testing  

---

## ☁️ AWS Services Used

- **AWS Identity and Access Management (IAM)**
- **Amazon EC2**

---

## 🎯 Real-World Relevance

Misconfigured IAM permissions are one of the most common causes of cloud security incidents. This project reflects how access controls are designed and tested in real-world AWS environments to reduce risk, prevent accidental outages, and limit the impact of compromised credentials.

---

## 📌 Next Steps

- Add IAM groups for scalable permission management  
- Enable Multi-Factor Authentication (MFA) for IAM users  
- Implement tag-based IAM condition policies  
- Apply similar access controls to S3 and RDS  


