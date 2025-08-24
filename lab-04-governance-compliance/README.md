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
- Resource with *tag applied* (failed due to restrictions however concept fully understood) ✅
  <img width="940" height="386" alt="image" src="https://github.com/user-attachments/assets/76a67dcd-254d-43f8-bc69-1c330c1e4719" />
- *Resource lock* created ✅
   <img width="940" height="386" alt="image" src="https://github.com/user-attachments/assets/3b669dd4-c565-45b5-bbcc-a43da2143c1f" />
- *Policy assignment* overview ✅
  <img width="940" height="426" alt="image" src="https://github.com/user-attachments/assets/9cf6b8db-6391-4142-93d2-47b1bdfb477a" />

---

## ✅ Outcome
- Learned how to apply *tags* for organization.  
- Created a *lock* to prevent accidental deletion.  
- Assigned a *policy* to enforce compliance.  

---

📌 Note: Lab performed in Microsoft Learn Sandbox. Some features may be restricted.
