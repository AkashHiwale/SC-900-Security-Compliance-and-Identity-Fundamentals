# 🗃️ Retention Labels

**Retention Labels** are part of **Microsoft Purview Information Governance**. They help organizations **manage the lifecycle of data** by specifying how long content should be **retained** and what should happen to it afterward (e.g., delete, review, or keep).

These labels are essential for meeting **legal**, **regulatory**, and **organizational** compliance requirements.

---

## 🎯 Purpose

- Ensure important data is **retained** for a specific period
- Automatically **delete** or **review** content when it's no longer needed
- Support **legal investigations**, **audits**, and **compliance mandates**
- Prevent premature deletion of business-critical or regulated content

---

## 🧰 Key Features

| Feature                        | Description |
|--------------------------------|-------------|
| **Retention Settings**         | Define how long content should be kept (e.g., 5 years) |
| **Trigger Conditions**         | Start retention based on creation date, last modified date, or labeled event |
| **Actions After Retention**    | Automatically delete, trigger review, or do nothing |
| **Manual or Auto Application** | Labels can be applied by users or automatically via policies |
| **Immutable Records**          | Content marked as a record can’t be modified or deleted |
| **Retention Policies vs. Labels** | Policies apply broadly; labels give more granular control |

---

## 🔄 Label Lifecycle Options

| Option                   | Behavior |
|--------------------------|----------|
| **Retain and then delete** | Keep content for x years, then delete |
| **Delete only**            | Delete content after x years |
| **Retain only**            | Keep content indefinitely, prevent deletion |

---

## 🗂️ Example Retention Labels

| Label Name       | Description                            | Action        |
|------------------|----------------------------------------|---------------|
| **Financial Docs - 7 Years** | Retain financial records for 7 years | Delete after 7 years |
| **HR Records - Indefinite** | Retain employment contracts forever   | Retain only     |
| **Marketing Drafts - 1 Year** | Auto-delete old content              | Delete after 1 year |

---

## 🌐 Where Retention Labels Apply

- **Exchange Online** (emails)
- **SharePoint Online**
- **OneDrive**
- **Microsoft Teams** (chats and channel messages)
- **Office apps** (Word, Excel, PowerPoint files stored in M365)

---

## ✅ Benefits

- Helps meet **legal and regulatory obligations**
- Reduces risk by **eliminating unnecessary data**
- Ensures **consistency** in data retention practices
- Prevents **accidental deletion** of critical content

---

## 📝 Exam Tips

- Retention labels define **how long** to keep content and **what to do** after the period.
- Can be applied **manually** by users or **automatically** through policies.
- You may be asked:  
  👉 *Which Microsoft feature allows you to define how long content is retained or deleted?*  
  ✅ Answer: **Retention Labels**

---