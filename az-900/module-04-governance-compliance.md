# Module 04 – Describe Azure Governance and Compliance Features

## 🎯 Learning Objectives
- Understand Azure governance and management tools.  
- Learn about subscriptions, management groups, and resource organization.  
- Explore Azure Policy and Blueprints.  
- Apply Role-Based Access Control (RBAC).  
- Use tags and locks to manage resources.  

---

## 🔑 Key Concepts

### Subscriptions & Management Groups
- *Subscription* → billing boundary, container for resources.  
- *Management Group* → organize multiple subscriptions, apply policies at scale.  

---

### Azure Policy
- Enforces rules for resources.  
- Example: Only allow VMs in a certain region.  
- Provides compliance reporting.  

---

### Azure Blueprints
- Package policies, role assignments, ARM templates.  
- Standardize environments (e.g., for compliance frameworks).  

---

### Role-Based Access Control (RBAC)
- Fine-grained access management.  
- Assign users/groups roles at different scopes:  
  - Management group  
  - Subscription  
  - Resource group  
  - Resource  

---

### Tags
- Key-value pairs to organize resources.  
- Examples: Environment = Production, Owner = IT.  
- Useful for billing and cost management.  

---

### Resource Locks
- Prevent accidental deletion or modification.  
- Types:  
  - *Read-only* → no changes allowed.  
  - *Delete* → prevents deletion only.  

---

### Azure Resource Manager (ARM)
- Deployment and management layer.  
- Consistent management across Azure services.  
- Supports templates for repeatable deployments.  

---

## 🛠️ Lab 04 (Practical)
- Apply a tag to a resource.  
- Create a resource lock.  
- Assign a simple policy (e.g., require tags on resources).  

---

## ✅ Summary
- Azure governance ensures resources are controlled, compliant, and organized.  
- Subscriptions & management groups organize resources at scale.  
- Azure Policy + Blueprints enforce compliance.  
- RBAC controls access.  
- Tags and locks provide additional governance and protection.
