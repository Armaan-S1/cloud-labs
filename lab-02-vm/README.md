# Lab 02 – Create a Virtual Machine in Azure

## 🎯 Objective
- Create a Windows Virtual Machine in Azure.  
- Explore networking (VNet, Subnet, NSG).  
- (Optional) Connect to the VM using RDP.  

---

## 📝 Steps

### 1. Resource Group (Sandbox)
- In the Microsoft Learn Sandbox, a resource group was automatically created:  
  *learn-b9a390af-e8e6-4376-b65e-59bcc8f76ad3*

### 2. Create the Virtual Machine
- In Azure Portal → *Virtual machines → + Create → Azure virtual machine*.  
- Basics tab:  
  - Resource group: learn-b9a390af-e8e6-4376-b65e-59bcc8f76ad3  
  - VM name: my-VM  
  - Region: (auto-selected by sandbox)  
  - Image: *Windows Server 2019 Datacenter*  
  - Size: Standard D2s v3 
  - Username: azureuser  
  - Password: (sandbox credentials)  
- Networking tab:  
  - Virtual Network auto-created by sandbox.  
  - NSG rule allowed RDP (3389).  
- Review + Create → *Create*.  

### 3. Verification
- VM shows as *Running* in Overview.  
- Resource group contains:  
  - VM  
  - Virtual Network  
  - Network Security Group  
  - Disk  
  - Public IP address  
- (Optional) Connect → RDP to open the VM desktop.  

---

## 📸 Screenshots
(Taken from Azure Portal after VM creation in Sandbox)  

- Resource Group learn-b9a390af-e8e6-4376-b65e-59bcc8f76ad3 ✅
<img width="940" height="452" alt="image" src="https://github.com/user-attachments/assets/7c9c3c08-e42e-4401-bbaf-8961c265d2be" />
 - VM Overview page ✅
<img width="940" height="624" alt="image" src="https://github.com/user-attachments/assets/ea28f1d9-af7a-427f-acb2-85f5d895e814" />
 - Networking tab ✅
<img width="1311" height="775" alt="image" src="https://github.com/user-attachments/assets/d49187f2-58bb-4939-b807-576463abf2ad" />
 - Connect → RDP screen ✅
<img width="1324" height="842" alt="image" src="https://github.com/user-attachments/assets/dd50c3e3-9130-4cf4-aec9-5a63b68b8f42" />
  

---

## ✅ Outcome
A Windows Virtual Machine was successfully deployed in the *Microsoft Learn Sandbox*.  
The VM, networking, and supporting resources were created automatically inside the sandbox resource group.  

---

📌 Note: As this lab was completed in the Microsoft Learn Sandbox, resource names and regions were auto-generated. RDP access may be restricted.
