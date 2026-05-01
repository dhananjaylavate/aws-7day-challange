**🔐 What is an AWS Role?**

**An AWS Role is a set of permissions that can be assumed (used temporarily) by users, applications, or services.**

👉 Unlike IAM users, a role does not have a username/password.

👉 It is used only when needed, and then access is dropped.**


**🧠 Simple Example (Real Life)**


**Imagine you work in an office:**

You are a developer 👨‍💻

One day, you need access to production servers (which is sensitive)

Instead of giving you permanent access ❌

Your company gives you a temporary “admin badge” (role) ✅

**You:** **Take the role (badge) ---> Do your work --> Give it back (access ends)**


**☁️ AWS Example**


**Let’s say you have an app running on a server:**

**The app needs to read files from storage (S3)**, **Instead of saving passwords in the app ❌  You assign a role to the server ✅**

**👉 That role gives permission to access S3 securely**


**🎯 When are Roles used?**

• **Access between AWS services (EC2 → S3)**

• **Temporary access for users**

•**Cross-account access (one AWS account accessing another)**


🚀 Final Thought


**IAM User = Permanent identity 👤**

**Role = Temporary access 🎫**


**👉 Roles are more secure because they avoid sharing long-term credentials.**
