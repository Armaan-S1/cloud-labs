# Lab 03 – Explore Microsoft Entra ID (Azure AD)

## 🎯 Objective
- Understand what Microsoft Entra ID (Azure AD) is.  
- Explore identity management in Azure.  
- Create and manage users.  
- Assign roles and groups.  

---

## 📝 Steps

### 1. Open Microsoft Entra ID
- In Azure Portal → search for *Microsoft Entra ID*.  
- Open the *Overview* page to see:  
  - Tenant name  
  - Tenant ID  
  - Primary domain  

### 2. Explore Users
- Go to *Users*.  
- View existing users in the tenant.  
- Create a new test user:  
  - Name: lab3-user  
  - User principal name: lab3-user@<tenantname>.onmicrosoft.com  
  - Assign a temporary password.  

### 3. Create a Group
- Go to *Groups → + New group*.  
- Group type: *Security*.  
- Name: Lab3-TestGroup.  
- Add lab3-user as a member.  

### 4. Assign a Role
- Go to *Users → lab3-user → Assigned roles → + Add assignment*  
- Assign the *Reader* role.  

---

## 📸 Screenshots
(Taken from Azure Portal after completing the tasks)  

- Entra ID Overview page ✅
  <img width="940" height="401" alt="image" src="https://github.com/user-attachments/assets/4de7e32d-c4b0-4aaf-82c2-75481dab1429" />
- Users list showing lab3-user ✅
  <img width="940" height="325" alt="image" src="https://github.com/user-attachments/assets/b817eafe-4cef-4301-8291-e759e61fb3eb" />
- Group Lab3-TestGroup with member ✅
  <img width="940" height="316" alt="image" src="https://github.com/user-attachments/assets/db651878-d2bc-4566-9cde-2ec92e0e02d9" />
- Role assignment for lab3-user ✅
  <img width="940" height="314" alt="image" src="https://github.com/user-attachments/assets/d45217ec-efee-4190-b558-2e326105b31c" />

---

## ✅ Outcome
- Microsoft Entra ID tenant explored.  
- A new user was created.  
- User added to a security group.  
- Role assigned to control access.  

---

📌 Note: This lab was completed in the Microsoft Learn Sandbox. Some features may be restricted.
