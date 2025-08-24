# Lab 04 – Azure Governance and Compliance

## 🎯 Objective
- Apply governance tools in Azure.  
- Use tags, locks, and policies to manage resources.  

---

## 📝 Steps

### 1. Apply a Tag
- In Azure Portal → select a resource (e.g., VM, Storage).  
- Under *Tags*, add:  
  - Key: Environment  
  - Value: Lab  
- Save changes.  

### 2. Create a Resource Lock
- Go to the same resource → *Locks*.  
- Add a lock:  
  - Name: Prevent-Delete  
  - Type: *Delete*.  

### 3. Assign a Policy
- In Azure Portal → search *Policy*.  
- Create a new policy assignment:  
  - Definition: Require a tag on resources  
  - Scope: Your sandbox subscription/resource group.  
- Save and check compliance.  

---

## 📸 Screenshots
- Resource with *tag applied* ✅  
- *Resource lock* created ✅  
- *Policy assignment* overview ✅  

---

## ✅ Outcome
- Learned how to apply *tags* for organization.  
- Created a *lock* to prevent accidental deletion.  
- Assigned a *policy* to enforce compliance.  

---

📌 Note: Lab performed in Microsoft Learn Sandbox. Some features may be restricted.
