# 🗄️ Azure Storage Service Encryption (SSE)

**Azure Storage Service Encryption (SSE)** automatically **encrypts your data at rest** in Azure Storage, including:

- **Blob Storage**
- **File Shares**
- **Queues**
- **Tables**

This ensures that all stored data is encrypted without requiring any changes to your application.

---

## 🎯 Purpose of SSE

- Automatically protect data at rest
- Meet **compliance and regulatory requirements**
- Provide **encryption without impacting performance**

---

## 🔐 How It Works

- **Encryption** occurs **automatically** before data is written to storage.
- **Decryption** occurs **automatically** during read operations.
- You don’t need to **modify code** to use encryption.

---

## 🔑 Encryption Key Options

| Option                        | Description |
|-------------------------------|-------------|
| **Microsoft-Managed Keys**     | Default option — Azure handles key creation and management |
| **Customer-Managed Keys (CMK)**| You manage your own keys in Azure Key Vault |
| **Customer-Provided Keys (CPK)**| You provide the key in each storage request (advanced use case) |

---

## 🧱 Key Features

| Feature                      | Description |
|------------------------------|-------------|
| **Automatic at-rest encryption** | Enabled by default for all Azure Storage |
| **Encryption algorithms**    | Uses AES 256-bit encryption (FIPS 140-2 compliant) |
| **No performance impact**    | Transparent to apps; same performance as unencrypted data |
| **Key Rotation Support**     | Supported with Customer-Managed Keys via Azure Key Vault |

---

## 🧰 Use Cases

- Storing **sensitive business data** in blob or file storage
- Complying with **data protection laws (GDPR, HIPAA, etc.)**
- Enforcing **organization-specific encryption policies**

---

## ✅ Best Practices

- Use **Customer-Managed Keys (CMK)** if you need control over key lifecycle
- Enable **soft delete and versioning** to protect from accidental data loss
- Use **Azure Monitor Logs** to audit key usage

---

## 📝 Exam Tips

- SSE automatically encrypts **all Azure Storage data at rest** using **AES-256**.
- By default, Azure uses **Microsoft-managed keys**, but you can use your own keys via **Azure Key Vault**.
- It is **transparent to users and apps** — no app changes needed.
- You may be asked:  
  👉 *Which Azure feature provides automatic encryption of data at rest in Azure Storage?*  
  ✅ Answer: **Azure Storage Service Encryption (SSE)**

---