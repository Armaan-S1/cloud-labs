# Module 09 – Describe Azure Storage Services

## 🌐 Overview
Azure provides multiple storage services to handle structured, semi-structured, and unstructured data.

---

## 📦 Azure Storage Types

### 1. Blob Storage
- Object storage for unstructured data (images, videos, backups).
- Supports hot, cool, and archive tiers for cost management.
- Scalable and highly durable.

### 2. Azure Files
- Fully managed file shares.
- Accessible over SMB or NFS.
- Can replace or extend on-premises file servers.

### 3. Queue Storage
- Message-based communication between components.
- Ensures decoupled, reliable processing.

### 4. Table Storage
- NoSQL key-value store.
- Schema-less design, good for flexible datasets.
- Low latency and high scalability.

---

## 🛡 Replication Options
- *LRS* – Locally Redundant Storage (within single datacenter).  
- *ZRS* – Zone Redundant Storage (across availability zones).  
- *GRS* – Geo Redundant Storage (replicates to another region).  
- *RA-GRS* – Read-Access Geo Redundant Storage (readable secondary).  

---

## 📌 Summary
- Azure Storage is versatile: Blob (objects), Files (SMB), Queues (messages), Tables (NoSQL).  
- Replication options provide durability and resilience.  
- Storage accounts unify access and configuration for these services.  

---
