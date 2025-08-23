# Lab 02 – Create a Virtual Machine in Azure

## 🎯 Objective
- Create a Windows Virtual Machine in Azure.  
- Configure basic networking (VNet, Subnet, NSG).  
- Connect to the VM using RDP.  

---

## 📝 Steps

### 1. Create a Resource Group
- Go to *Azure Portal* → Search for *Resource groups*.  
- Click *+ Create* → Name it lab2-rg.  
- Choose your subscription + region.  
- Click *Review + Create* → *Create*.  

### 2. Create a Virtual Machine
- Go to *Virtual machines* → *+ Create → Azure virtual machine*.  
- Basics tab:  
  - Resource group: lab2-rg  
  - VM name: lab2-vm  
  - Region: (same as resource group)  
  - Image: *Windows Server 2019 Datacenter*  
  - Size: (e.g., B1s – free tier eligible)  
  - Username: azureuser  
  - Password: (choose strong password)  
- Networking tab:  
  - New Virtual Network (VNet) created automatically.  
  - Allow RDP (3389).  
- Review + Create → *Create*.  

### 3. Connect to the VM
- Once deployment is complete → Go to VM → *Connect → RDP*.  
- Download the RDP file and open it.  
- Login with the credentials you set.  

### 4. Verification
- Open the VM desktop.  
- Take a screenshot of the Windows Server desktop.  

---

## 📸 Screenshots
- Resource group created ✅  
- VM deployment ✅  
- RDP connection ✅  

(Screenshots are stored locally for now, will upload later)  

---

## ✅ Outcome
You successfully deployed and connected to a Windows Virtual Machine in Azure.
