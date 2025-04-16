# EHRM-AWS-Security-Project

## 🔐 Mission-Ready: Hardened AWS Security for the VA's Electronic Health Record Modernization (EHRM) Project

**Author:** Diamond Williams  
**Status:** Work in Progress  
**Tools Used:** AWS, Terraform, IAM, CloudTrail, CloudWatch, Pacu (AWS Pentesting)  
**Objective:** Secure an AWS environment, automate security configurations, and conduct vulnerability testing for the U.S. Department of Veterans Affairs (VA).

---

## 🚀 Why I Started This Project

Securing cloud environments is one of today’s most critical and complex challenges — especially for healthcare institutions managing sensitive patient data. With the VA’s EHRM initiative, safeguarding the health records of millions of veterans became more than just a project — it became a mission.

I initiated this hands-on project to:
- Identify and fix AWS misconfigurations
- Automate infrastructure with Terraform
- Implement airtight IAM security
- Prepare for real-world penetration testing using Pacu

The end goal? To build and validate a secure, compliant AWS environment — one ready for real-world threats and audits.

---

## 🧱 Project Breakdown

### **Phase | Challenges Faced | Current Progress | Next Steps**
![image](https://github.com/user-attachments/assets/96c9bc7d-7ba1-4578-b32e-263fe3cb82af)

---

### ⚙️ **Challenges I Faced (and Solved)**

#### 1. AWS Misconfigurations & Terraform Conflicts  
**Problem:** Duplicate resources, IAM conflicts, and state drift.  
**Solutions:**  
- ✅ Used terraform `state rm` and `terraform import` to correct state issues  
- ✅ Modularized resources for maintainability  
- ✅ Refactored policy attachments and role bindings

#### 2. IAM Security Missteps  
**Problem:** Over-permissive policies = serious risk for privilege escalation  
**Solutions:**  
- ✅ Implemented Least Privilege Access  
- ✅ Used AWS IAM Access Analyzer for policy audits  
- ✅ Enforced RBAC and explicit deny conditions

#### 3. Logging & Monitoring Gaps  
**Problem:** CloudTrail wasn’t tracking all API events, and CloudWatch logs were incomplete.  
**Solutions:**  
- ✅ Centralized logs in an encrypted S3 bucket  
- ✅ Set proper retention policies and region-wide trails  
- ✅ Created CloudWatch alarms for suspicious activity (e.g., failed logins, root usage)

---

## 🧪 What's Next: Penetration Testing & Final Hardening

- 🔜 Final security validation using Pacu (AWS exploitation framework)  
- 🔜 Simulating common misconfigurations (e.g., privilege escalation paths, leaked credentials)  
- 🔜 Remediating any vulnerabilities discovered  
- 🔜 Ensuring compliance with NIST, HIPAA, and federal cloud security benchmarks

---

## 🏥 Why This Project Matters

- ✅ Veterans' data is sacred. This project helps ensure it stays secure.  
- ✅ Small businesses and startups often misconfigure AWS — my approach can be scaled to help them too.  
- ✅ Real-world testing (not just theory) makes this project stand out in today's competitive security landscape.

---

## 🔚 Final Thoughts & Call to Action

This is more than just a portfolio piece — it's a living, breathing cloud security blueprint. And I'm just getting started.  

🔥 Follow my journey to the final pentesting results and see how I transform AWS environments into fortified infrastructure.

---

## 📌 Links
- **GitHub Repo:** (https://github.com/Dwil1730/EHRM-AWS-Security-Project)
- **LinkedIn:** (https://www.linkedin.com/in/diamondw1730/)
- **Need help hardening your AWS environment?** ( diamondwilliams1730@gmail.com)

---

## 📊 Project Architecture
![Image 4-16-25 at 10 49 AM](https://github.com/user-attachments/assets/90999767-7196-4900-a9d2-d20c884af35d)



