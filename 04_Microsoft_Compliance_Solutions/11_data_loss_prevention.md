# 🚫 Data Loss Prevention (DLP)

**Data Loss Prevention (DLP)** is a feature in Microsoft Purview that helps organizations **detect**, **monitor**, and **protect sensitive information** from being unintentionally shared, leaked, or mishandled.

DLP policies are applied across Microsoft 365 services to **prevent data breaches** and maintain **compliance** with regulatory requirements.

---

## 🎯 Purpose

- Protect sensitive data like **credit card numbers**, **social security numbers**, **health records**, etc.
- Prevent **accidental sharing** via email, Teams, or cloud storage
- Comply with **regulatory standards** such as GDPR, HIPAA, PCI-DSS
- Educate users through **policy tips** while they work

---

## 🧰 Key Features

| Feature                    | Description |
|----------------------------|-------------|
| **DLP Policies**            | Rules to monitor and restrict sensitive data sharing |
| **Sensitive Info Types**    | Predefined patterns like PII, bank details, or custom types |
| **Policy Tips**             | In-product notifications that warn users of policy violations |
| **Monitoring & Reporting**  | View policy matches, alerts, and user actions in compliance center |
| **Actions on Violation**    | Block sharing, encrypt content, notify user/admin |
| **Custom Locations**        | Apply policies to specific workloads like Exchange, OneDrive, Teams, SharePoint |

---

## 🛡️ Common Protection Scenarios

- Block sending **credit card numbers** via email outside the organization
- Prevent uploading **patient records** to personal OneDrive
- Warn users before sending confidential documents externally

---

## 📍 Where DLP Can Be Applied

| Platform         | Support |
|------------------|---------|
| **Exchange Online** | ✅ Emails |
| **OneDrive for Business** | ✅ Files |
| **SharePoint Online** | ✅ Documents |
| **Microsoft Teams** | ✅ Chat and channel messages |
| **Endpoint (Windows 10/11)** | ✅ Files copied to USB, etc. |

---

## 🧠 How It Works

1. Define **sensitive information types** and **conditions**
2. Create **DLP policy** and select locations (e.g., SharePoint, Exchange)
3. Configure **actions** (e.g., block, notify, audit)
4. Apply and monitor through the **Microsoft Purview compliance portal**

---

## ✅ Benefits

- Helps **prevent data leaks** without hindering productivity
- Increases **user awareness** via real-time policy tips
- Reduces **compliance risk**
- Covers **cloud**, **email**, and **endpoint** scenarios

---

## 📝 Exam Tips

- DLP helps **detect and prevent accidental sharing** of **sensitive data**.
- It works across **Microsoft 365 services** including email, files, Teams, and endpoints.
- You may be asked:  
  👉 *Which feature helps protect sensitive data from being shared outside the organization unintentionally?*  
  ✅ Answer: **Data Loss Prevention (DLP)**

---