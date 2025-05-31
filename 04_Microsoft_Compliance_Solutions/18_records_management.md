# 🗂️ Records Management in Microsoft 365

**Records Management** in **Microsoft Purview** allows organizations to **classify, retain, declare, and dispose** of content as **official records** in compliance with **regulatory**, **legal**, or **business** requirements.

It ensures that important business information is preserved in a **secure, tamper-proof** manner while enabling controlled deletion when no longer needed.

---

## 🎯 Purpose

- Maintain **legal and regulatory compliance**
- Preserve **business-critical records**
- Prevent **accidental or unauthorized deletion**
- Enable **auditable records** with proper lifecycle control

---

## 🔐 Key Concepts

| Concept                   | Description |
|---------------------------|-------------|
| **Retention Labels**       | Used to apply retention or deletion policies to content |
| **Record Label**           | A special type of retention label that declares content as a **record** |
| **Regulatory Record**      | A stricter record that **cannot be modified or deleted**, even by admins |
| **Disposition Review**     | Lets reviewers decide whether content should be deleted at the end of its retention period |
| **Proof of Disposition**   | Maintains an audit trail for deleted records |

---

## 🧰 Core Features

| Feature                         | Description |
|----------------------------------|-------------|
| **Manual or automatic labeling** | Apply record labels manually or based on conditions |
| **Locking mechanism**           | Prevents edits/deletion of declared records |
| **Compliance boundaries**       | Ensures data governance across departments or regions |
| **Disposition reviews**         | Enables human review before record deletion |
| **Audit logs**                  | Tracks all record-related activities for accountability |

---

## 🏛️ Types of Records

| Type                 | Behavior |
|----------------------|----------|
| **Standard Record**   | Can be modified or deleted by authorized users |
| **Regulatory Record** | Locked; no one (even admins) can modify or delete it without following regulatory protocols |

---

## 🧾 Use Cases

| Scenario                                | Use |
|-----------------------------------------|-----|
| Financial or legal documentation        | Declare as **regulatory records** |
| Employee contracts and HR policies      | Apply **retention labels** with disposition reviews |
| Healthcare records                      | Ensure **compliance** with HIPAA-like regulations |
| Policy change history                   | Preserve past versions for **audit readiness** |

---

## ✅ Benefits

- Helps meet **industry regulations** and **legal standards**
- Maintains **data integrity and authenticity**
- Supports **governance policies** across Microsoft 365
- Enables **custom retention schedules** with granular control

---

## 📝 Exam Tips

- Use **Records Management** to manage content that must be **preserved and audited**.
- A **regulatory record** cannot be **edited or deleted** once applied.
- You may be asked:  
  👉 *Which Microsoft 365 feature is used to declare documents as records for compliance purposes?*  
  ✅ Answer: **Microsoft Purview Records Management**

---