# 🛡️ Zero Trust Security Model

The **Zero Trust Model** is a modern security approach based on the principle:  
> "**Never trust, always verify**".

Instead of assuming trust within a network perimeter, Zero Trust requires **continuous verification of identity, device health, and context**—no matter where the request originates.

---

## 🔍 Why Zero Trust?

- Traditional security assumed anything inside the corporate network was trustworthy.
- With **remote work**, **cloud services**, and **mobile devices**, that perimeter no longer exists.
- Zero Trust helps prevent data breaches by reducing implicit trust and requiring **explicit verification** at every step.

---

## 🧱 Core Principles of Zero Trust

| Principle                          | Description |
|------------------------------------|-------------|
| **Verify explicitly**              | Authenticate and authorize based on all available data points (user identity, device, location, etc.). |
| **Use least privilege access**     | Limit access to only what users need using just-in-time (JIT), just-enough-access (JEA), and role-based access controls (RBAC). |
| **Assume breach**                  | Design with the assumption that attackers are already inside—segment networks and monitor continuously. |

---

## 🧰 Microsoft Implementation of Zero Trust

Microsoft applies Zero Trust across **six foundational pillars**:

| Pillar          | Description |
|-----------------|-------------|
| **Identities**   | Ensure identities (users, devices, services) are verified and use strong authentication like MFA. |
| **Devices**      | Ensure devices are compliant and healthy before granting access. |
| **Applications** | Apply controls to SaaS and on-prem apps, including single sign-on (SSO) and app-based conditional access. |
| **Data**         | Classify and protect data using encryption, DLP, and sensitivity labels. |
| **Infrastructure** | Monitor and segment infrastructure, apply least privilege on workloads. |
| **Network**      | Segment access and encrypt data in transit; use micro-segmentation. |

---

## 🛡️ Technologies That Support Zero Trust in Azure

- **Azure AD Conditional Access**
- **Azure AD Identity Protection**
- **Microsoft Defender for Identity / Endpoint**
- **Microsoft Purview (for data classification and DLP)**
- **Microsoft Intune (for device compliance and management)**
- **Azure Firewall, NSGs, and Private Link (for network segmentation)**

---

## 📝 Exam Tips

- Zero Trust assumes **no device or user is trusted by default**, even inside the corporate network.
- Know the **three core principles**: **verify explicitly**, **least privilege access**, **assume breach**.
- Understand that **identities, devices, data, apps, networks, and infrastructure** are all part of the Zero Trust model.
- Be familiar with tools like **Conditional Access**, **MFA**, and **Microsoft Defender** that help implement Zero Trust.
- Expect questions that assess **how Zero Trust limits lateral movement** in case of compromise and **reduces risk**.

---