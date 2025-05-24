# 🔗 Hybrid Identities & Managed Identities

---

## 🧩 What is a Hybrid Identity?

A **hybrid identity** is when an organization uses both **on-premises Active Directory (AD)** and **Azure Active Directory (Azure AD)** together.

This setup allows users to:
- Use a **single identity** for on-prem and cloud resources.
- Sign in to cloud services using **on-prem credentials**.

---

### 🔁 How Hybrid Identity Works

Hybrid identity is made possible through:

| Tool                  | Purpose |
|------------------------|---------|
| **Azure AD Connect**   | Synchronizes users/groups from on-prem AD to Azure AD. |
| **Password Hash Sync (PHS)** | Hashes passwords from AD and syncs them to Azure AD. |
| **Pass-through Authentication (PTA)** | Authenticates directly against on-prem AD without storing hashes in Azure AD. |
| **Federation (ADFS)** | Uses on-prem federation server to handle authentication. |

---

### 🛠️ Hybrid Identity Options

| Method                      | Description |
|-----------------------------|-------------|
| **Password Hash Sync (PHS)** | Easiest to set up. Syncs hashes to cloud. |
| **Pass-through Authentication (PTA)** | Authenticates via on-prem AD. Passwords never stored in cloud. |
| **Federation (ADFS)**        | On-prem federation system handles authentication. Used in complex orgs. |

---

## ☁️ What are Managed Identities?

**Managed Identities** are identities automatically managed by Azure for use with Azure services.  
They eliminate the need to manage credentials in code.

> Think of them as a "built-in service account" for your Azure resources.

---

### 🔐 Types of Managed Identities

| Type                      | Description |
|---------------------------|-------------|
| **System-assigned**       | Tied to a specific resource (like a VM). Automatically created and deleted with the resource. |
| **User-assigned**         | Standalone identity that can be assigned to multiple resources. Managed independently. |

---

### ✅ Use Cases

- Access **Azure Key Vault** without hardcoding secrets.
- Allow an **Azure Function** to call an **Azure Storage Account** securely.
- Let a **VM** authenticate to Azure services using its **system-assigned identity**.

---

## 🛡️ Security Benefits

| Benefit                        | Description |
|-------------------------------|-------------|
| **Credential-less access**     | No need to store credentials in code or config files. |
| **Token-based authentication** | Uses OAuth 2.0 tokens to access resources. |
| **Scoped permissions**         | Uses RBAC to define exactly what resources the identity can access. |

---

## 📝 Exam Tips

- **Hybrid identity** = Combine **on-prem AD** + **Azure AD** using **Azure AD Connect**.
- Know the three methods: **PHS**, **PTA**, and **Federation**.
- **Managed identities** are used for **Azure services to authenticate to other Azure services** securely.
- You don’t manage credentials with **managed identities** — Azure handles it automatically.
- Managed identities use **RBAC** for access control.
- Expect questions like:  
  👉 *Which solution allows VMs to securely access Azure resources without credentials?*  
  ✅ Answer: **Managed Identity**

---