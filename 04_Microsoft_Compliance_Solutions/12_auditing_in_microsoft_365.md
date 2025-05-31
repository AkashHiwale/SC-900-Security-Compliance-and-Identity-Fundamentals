# 📋 Auditing in Microsoft 365

**Auditing in Microsoft 365** helps organizations **track user and admin activity** across Microsoft services like **Exchange**, **SharePoint**, **OneDrive**, **Teams**, and **Azure AD**.

Audit logs are crucial for **compliance**, **security investigations**, and **forensic analysis**.

---

## 🎯 Purpose

- Monitor and investigate **suspicious activities**
- Maintain **compliance** with industry regulations
- Enable **forensic investigations** after a breach
- Keep track of **user and admin actions** across services

---

## 🧰 Key Features

| Feature                  | Description |
|--------------------------|-------------|
| **Audit Log Search**      | Centralized tool in Microsoft Purview to search logs |
| **Unified Audit Log**     | Tracks activity across multiple Microsoft 365 services |
| **Custom Search Filters** | Search by user, activity type, date, or file |
| **Export Logs**           | Export logs for external review or long-term storage |
| **Advanced Audit (Microsoft 365 E5)** | Offers longer retention (up to 1 year) and deeper insights |

---

## 🛠️ What Can Be Audited?

| Service            | Examples of Auditable Activities |
|--------------------|----------------------------------|
| **Exchange Online** | Sent emails, mailbox access |
| **SharePoint/OneDrive** | File access, downloads, deletions |
| **Teams**          | Message edits/deletes, file sharing |
| **Azure AD**       | Login attempts, MFA changes, role assignments |
| **Power Platform** | Flows triggered, app launches |

---

## 🔍 How It Works

1. **Audit logging is enabled by default** for all Microsoft 365 organizations.
2. Admins can access logs from the **Microsoft Purview compliance portal**.
3. Logs can be filtered by:
   - Date and time
   - User
   - Activity type
   - File/folder
4. Logs are **retained for 90 days by default** (up to 1 year with Advanced Audit).

---

## 🧾 Example Use Cases

- Investigating who deleted or accessed a sensitive document
- Monitoring **admin role changes**
- Detecting **unauthorized access attempts**
- Tracking **data exfiltration**

---

## ✅ Benefits

- Provides **visibility and transparency** into user and system behavior
- Enables **security incident response**
- Helps with **compliance and regulatory reporting**
- Useful for **legal investigations** (e.g., eDiscovery)

---

## 📝 Exam Tips

- Audit logs help track **user and admin activity** across M365 services.
- Accessed through the **Microsoft Purview compliance portal**.
- You may be asked:  
  👉 *Which Microsoft 365 feature allows administrators to track file access and user actions across services?*  
  ✅ Answer: **Audit Logs / Unified Audit Log**

---