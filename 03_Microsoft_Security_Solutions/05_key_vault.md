# 🔑 Azure Key Vault

**Azure Key Vault** is a **cloud service** that helps securely **store and manage sensitive information**, such as:

- **Secrets** (API keys, passwords, connection strings)
- **Keys** (encryption keys)
- **Certificates**
- **Secrets for TLS/SSL or application config**

It ensures **centralized access control**, **logging**, and **auditing** of secrets and cryptographic keys.

---

## 🎯 Purpose of Azure Key Vault

- Protect **application secrets** and sensitive data
- Store **cryptographic keys** used for encryption/decryption
- Manage **certificates** for secure communications
- Enable **secure access** using **Azure Active Directory (Azure AD)**

---

## 🧱 Key Vault Components

| Component   | Description |
|-------------|-------------|
| **Secrets** | Small pieces of data (like connection strings or passwords) |
| **Keys**    | RSA/EC keys used for encryption, decryption, signing |
| **Certificates** | Manage SSL/TLS certificates |
| **Managed HSM** | Hardware-backed key store for high security |

---

## 🔐 Key Features

| Feature                    | Description |
|----------------------------|-------------|
| **Secure Storage**         | Encrypted at rest using Azure-managed or customer-managed keys |
| **Access Policies**        | Define who can access what (e.g., get, list, set, delete) |
| **Logging & Auditing**     | Integrated with Azure Monitor and Azure Sentinel |
| **Key Rotation**           | Automatically rotate keys and secrets |
| **Soft Delete & Purge Protection** | Prevent accidental deletion or loss of secrets |
| **Backup and Restore**     | Securely back up and restore secrets/keys |

---

## 🧠 How It Works

1. An app or user requests access to a secret or key.
2. Azure AD authenticates the caller.
3. If authorized by Key Vault **Access Policy or RBAC**, access is granted.
4. App retrieves the secret or performs cryptographic operation.

---

## 🧰 Use Cases

- Storing database passwords securely
- Encrypting virtual machine disks using **Azure Disk Encryption**
- Signing certificates for secure communication
- Securing secrets in **DevOps pipelines**

---

## 🔐 Integration Options

- Azure Functions, Logic Apps, App Services
- Azure VMs, AKS, and Azure DevOps
- **Key Vault References** in App Configuration

---

## 📝 Exam Tips

- Azure Key Vault stores **secrets, keys, and certificates**.
- Secured using **Azure AD authentication** and **access policies**.
- Avoid storing secrets in **code or config files** — use Key Vault instead.
- You may be asked:  
  👉 *Which Azure service should you use to securely store application secrets and encryption keys?*  
  ✅ Answer: **Azure Key Vault**

---