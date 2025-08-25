# AZ-900 Module 5 – Describe Azure Cost Management and Service Level Agreements

---

## Key Concepts

### 1. Factors Affecting Cost
- *Resource type* – VM, Storage, Networking, etc.
- *Usage* – Pay only for what you use.
- *Location (Region)* – Prices vary by region.
- *Billing options* – Pay-as-you-go, Reserved Instances, Spot pricing.
- *Support Plans* – Different tiers (Developer, Standard, Professional Direct).
- *Licensing* – Hybrid Use Benefit can reduce costs.

---

### 2. Tools for Managing Cost
- *Azure Pricing Calculator* – Estimate costs before deployment.
- *Total Cost of Ownership (TCO) Calculator* – Compare Azure vs. on-premises.
- *Azure Cost Management + Billing* – Monitor spend, create budgets, set alerts.

---

### 3. Service Level Agreements (SLA)
- Microsoft guarantees a *financially-backed uptime percentage* for each service.
- Examples:
  - *VMs*: 99.9% uptime for single-instance VMs with Premium SSD.
  - *VMs in Availability Zones*: Up to 99.99% uptime.
  - *Storage*: 99.9%+ depending on replication.
- SLAs impact *application design*:
  - Use redundancy (Availability Sets, Zones, Regions) to achieve higher SLAs.

---

### 4. Service Lifecycle
- Services go through stages: *Preview → General Availability → Deprecated*.
- SLA typically applies only once a service reaches *General Availability (GA)*.

---

## Summary
- Azure provides multiple tools to *predict and control costs*.
- SLAs are critical for designing *highly available and reliable solutions*.
- Understanding cost + SLA helps balance *performance, reliability, and budget*.
