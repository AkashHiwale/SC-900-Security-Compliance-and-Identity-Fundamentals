# 🔐 Information Protection

**Information Protection** refers to the tools, policies, and processes used to **classify**, **label**, and **protect data** based on its sensitivity and business value — whether the data is at rest, in use, or in transit.

Microsoft provides **Purview Information Protection** as the core solution for data protection across Microsoft 365 and Azure.

---

## 🎯 Purpose of Information Protection

- Prevent **data leaks** and **unauthorized access**
- Meet **regulatory compliance** (e.g., GDPR, HIPAA)
- Protect **sensitive and confidential data**
- Enable users to handle information **securely and consistently**

---

## 🧰 Key Concepts

| Term                      | Description |
|---------------------------|-------------|
| **Sensitivity Labels**    | Tags applied to documents, emails, and containers (e.g., Confidential, Public) |
| **Labeling**              | Can be **manual**, **recommended**, or **automatic** based on content |
| **Encryption**            | Protects data so only authorized users can access it |
| **Content Marking**       | Adds headers, footers, or watermarks to documents |
| **Rights Management (RMS)** | Controls actions (e.g., view, print, forward) on labeled content |

---

## 🔒 How Labels Work

1. **Label is created** in Microsoft Purview.
2. **Assigned manually** by users or **automatically** using:
   - Keywords
   - Sensitive info types (e.g., credit card numbers)
   - Machine learning models
3. Once applied, the label can:
   - Encrypt the content
   - Apply access restrictions
   - Add visual markings

---

## 🔄 Data Lifecycle Coverage

| Data State     | Protection Methods |
|----------------|--------------------|
| **At Rest**    | Encryption, access control, retention policies |
| **In Transit** | TLS encryption, secure file transfer protocols |
| **In Use**     | Labeling, rights management, monitoring, DLP |

---

## ✅ Benefits

- Prevents **accidental data exposure**
- Applies **consistent policies** across platforms (M365, Azure, endpoints)
- Enhances **visibility and control** over sensitive data
- Supports **user awareness and accountability**

---

## 📝 Exam Tips

- Information Protection involves **labeling, encryption, and access control**.
- **Sensitivity labels** help classify and protect data based on its sensitivity.
- You may be asked:  
  👉 *What tool helps apply labels and protect documents/emails based on content sensitivity?*  
  ✅ Answer: **Microsoft Purview Information Protection**

---