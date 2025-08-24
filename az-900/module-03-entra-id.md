# Module 03 – Describe Core Microsoft Entra ID (Azure AD) Concepts

## 🎯 Learning Objectives
- Understand what Microsoft Entra ID (Azure Active Directory) is.  
- Explore authentication and authorization.  
- Learn about users, groups, and roles.  
- Understand identity governance features.  
- Explore authentication methods (MFA, SSPR).  

---

## 🔑 Key Concepts

### What is Microsoft Entra ID?
- Cloud-based identity and access management service.  
- Provides *single sign-on (SSO), **multi-factor authentication (MFA), and **conditional access*.  
- Manages access to Microsoft 365, Azure resources, SaaS apps, and custom apps.  

---

### Identity vs. Access
- *Authentication* → Verifies who you are (password, MFA, biometric).  
- *Authorization* → Decides what you can do (roles, RBAC).  

---

### Users
- Individual identities stored in Entra ID.  
- Can be created manually, synced from on-prem AD, or invited as guests.  

---

### Groups
- Collections of users for easier management.  
- Types:  
  - *Security groups* → Control access to resources.  
  - *Microsoft 365 groups* → Collaboration in Teams, Outlook, SharePoint.  

---

### Roles
- Entra ID uses *role-based access control (RBAC)*.  
- Examples:  
  - *Global Administrator* → Full access to tenant.  
  - *User Administrator* → Can manage users.  
  - *Reader* → View-only permissions.  

---

### Authentication Methods
- *Password* (basic).  
- *Multi-Factor Authentication (MFA)* → adds a second layer of security.  
- *Self-Service Password Reset (SSPR)* → users reset their own passwords.  

---

### Conditional Access
- Allows administrators to enforce policies.  
- Example: Require MFA only when signing in from outside the corporate network.  

---

## 🛠️ Lab 03 (Practical)
- View Entra ID tenant.  
- Create a new user.  
- Create a security group.  
- Add user to group.  
- Assign a role (e.g., Reader).  

---

## ✅ Summary
- Microsoft Entra ID is Azure’s identity and access management service.  
- Provides authentication (login) and authorization (permissions).  
- Users, groups, and roles simplify identity management.  
- MFA and Conditional Access add extra security.
