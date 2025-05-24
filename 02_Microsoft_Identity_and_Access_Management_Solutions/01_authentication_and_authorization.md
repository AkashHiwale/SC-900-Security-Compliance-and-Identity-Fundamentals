# 🔐 Authentication vs Authorization

In cloud security, **authentication** and **authorization** are two fundamental concepts used to control access to resources. They work together, but serve **different purposes**.

---

## 🧾 What is Authentication?

**Authentication** is the process of **proving your identity**.

- It's about answering the question:  
  👉 *“Who are you?”*

### ✅ How Authentication Works

When a user attempts to sign in, the system verifies:
- **Username**
- **Password**
- Additional factors (if MFA is enabled)

If credentials match, the identity is **authenticated**.

### 🔑 Common Authentication Methods

| Method                          | Description |
|----------------------------------|-------------|
| **Password-based**               | Traditional method; less secure alone. |
| **Multi-Factor Authentication (MFA)** | Requires a second factor like phone app or OTP code. |
| **Biometric**                    | Uses fingerprint, face recognition, etc. |
| **Smart cards / Certificates**   | Secure hardware or software-based authentication. |

---

## 🔓 What is Authorization?

**Authorization** is the process of **granting access** to resources after authentication.

- It's about answering the question:  
  👉 *“What can you do?”*

Authorization determines what:
- **Resources** the user can access
- **Actions** they can perform (read, write, delete)

It’s enforced using **roles**, **policies**, and **permissions**.

---

## ⚖️ Authentication vs Authorization – Key Differences

| Feature            | Authentication              | Authorization                  |
|--------------------|------------------------------|---------------------------------|
| **Purpose**         | Verifies identity            | Grants access to resources      |
| **Question**        | "Who are you?"               | "What are you allowed to do?"   |
| **Occurs**          | First                        | After authentication            |
| **Technology**      | Passwords, MFA, Biometrics   | RBAC, ACLs, Policies            |
| **Example**         | Login with username & MFA    | Access files based on user role |

---

## 🔐 Azure Implementation

| Feature                      | Authentication | Authorization |
|------------------------------|----------------|---------------|
| **Azure AD Sign-in**         | ✅              | ❌             |
| **Conditional Access**       | ✅              | ❌             |
| **Azure RBAC**               | ❌              | ✅             |
| **Permissions on resources** | ❌              | ✅             |

---

## 📝 Exam Tips

- **Authentication = identity verification**, **Authorization = access control**.
- Azure AD handles **authentication** using protocols like OAuth 2.0 and SAML.
- **RBAC** and **Conditional Access** are used to implement **authorization** in Azure.
- You may get questions that ask:  
  👉 *Which service is responsible for authenticating users in Azure?* (Answer: **Azure AD**)  
  👉 *Which mechanism is used to grant access to Azure resources?* (Answer: **Azure RBAC**)

---