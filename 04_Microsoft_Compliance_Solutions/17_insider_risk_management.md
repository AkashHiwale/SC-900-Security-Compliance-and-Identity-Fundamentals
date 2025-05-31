# 🧠 Insider Risk Management in Microsoft 365

**Insider Risk Management** in **Microsoft Purview** helps organizations **detect, investigate, and respond** to risky user behavior that could lead to **data leaks**, **security breaches**, or **regulatory violations**.

It’s designed to protect against **malicious, negligent, or compromised insiders** using Microsoft 365 tools and data.

---

## 🎯 Purpose

- Identify **potential insider threats**
- Monitor risky behavior across Microsoft 365
- Support **early detection** and **investigation**
- Ensure **data protection** and **compliance**

---

## 🧰 Key Capabilities

| Feature                      | Description |
|-----------------------------|-------------|
| **Risk policies**            | Detect specific behaviors (e.g., data exfiltration, policy violations) |
| **Templates**                | Built-in policy templates for common insider risk scenarios |
| **Signals integration**      | Uses signals from Microsoft 365 (e.g., DLP alerts, SharePoint downloads) |
| **Anonymization**            | Keeps user identities hidden during investigation phase to prevent bias |
| **Alert dashboards**         | Central location to review and act on alerts |
| **Case management**          | Track and document investigations |

---

## ⚠️ Risk Scenarios Covered

| Scenario                        | Example |
|----------------------------------|---------|
| **Data leaks**                   | Uploading sensitive files to personal cloud |
| **Security violations**          | Disabling DLP alerts or encrypting sensitive emails improperly |
| **Regulatory non-compliance**    | Downloading regulated data and sharing externally |
| **User disgruntlement or exit**  | Mass file downloads before resignation notice |

---

## 📦 Integrated Signals

- Microsoft Defender for Endpoint
- Microsoft Defender for Cloud Apps
- Microsoft Purview DLP
- Azure AD (risky sign-ins, password reset)
- Microsoft 365 usage analytics

These inputs enhance detection of **intentional or unintentional risk** behaviors.

---

## 🧾 Example Policy Templates

| Template Name                  | Focus |
|--------------------------------|-------|
| **Data leaks by departing users** | Track file movements near termination |
| **Data theft by priority users**  | Monitor execs or users in sensitive roles |
| **General data leaks**            | Catch uploads to personal storage |
| **Security policy violations**    | Detect disabled security tools or risky activities |

---

## ✅ Benefits

- Proactively mitigates **internal threats**
- Helps ensure **data security** and **regulatory compliance**
- Supports **objective investigations** with anonymized workflows
- Centralized case and alert management

---

## 📝 Exam Tips

- **Insider Risk Management** uses **behavioral analytics and Microsoft 365 signals** to detect risky activities.
- Policies can monitor actions like **mass downloads**, **email forwarding**, and **data uploads**.
- You may be asked:  
  👉 *Which Microsoft Purview feature detects potential threats from within an organization?*  
  ✅ Answer: **Insider Risk Management**

---