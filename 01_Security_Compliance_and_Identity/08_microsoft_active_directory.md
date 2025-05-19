# 🗂️ Microsoft Active Directory (AD)

**Microsoft Active Directory (AD)** is an **on-premises** identity and access management service that stores information about objects on a network and makes this information easy for administrators and users to find and use.

---

## 🧠 What is Active Directory?

Active Directory is a **directory service** developed by Microsoft that runs on Windows Server and is used to:

- Store user accounts, passwords, computers, and groups.
- Authenticate and authorize users and devices in a Windows domain.
- Manage policies using **Group Policy Objects (GPOs)**.
- Enable **Single Sign-On (SSO)** within the domain.

---

## 🧱 Key Components

| Component         | Description |
|------------------|-------------|
| **Domain**        | A logical group of objects (users, computers, devices) within a network. |
| **Forest**        | A collection of one or more domains that share a common schema and global catalog. |
| **Organizational Unit (OU)** | A container for organizing users, groups, and computers. OUs help apply group policies. |
| **Domain Controller (DC)** | A server that runs Active Directory services and handles authentication and directory requests. |
| **Group Policy**  | Used to centrally manage security settings and user configurations in an AD environment. |

---

## 🔑 Capabilities

- Centralized user and group management
- Authentication using **Kerberos**
- Secure access control via policies
- Integration with legacy applications
- Can synchronize with **Azure Active Directory** using **Azure AD Connect**

---

## ☁️ Active Directory vs Azure AD

| Feature                      | Active Directory (AD)             | Azure Active Directory (Azure AD)         |
|-----------------------------|-----------------------------------|-------------------------------------------|
| Type                        | On-premises directory             | Cloud-based identity platform             |
| Protocols                   | Kerberos, LDAP                    | OAuth 2.0, OpenID Connect, SAML            |
| Device Management           | AD-joined devices                 | Azure AD-registered/joined devices        |
| App Authentication          | Limited to Windows apps           | Supports web/mobile/cloud apps            |
| Group Policy Support        | ✅ Yes                             | ❌ No (Use Intune for policies)            |
| Federation & SSO            | Limited                           | Broad support with modern auth protocols  |

---

## 🧩 When to Use

- Traditional on-premises environments with domain-joined devices.
- Organizations with apps that rely on **Kerberos or NTLM**.
- Hybrid environments when used together with **Azure AD** via **Azure AD Connect**.

---

## 📝 Exam Tips

- Know that **Active Directory** is the **on-premises identity provider**.
- Understand how **AD** differs from **Azure AD** — especially in **protocols** and **application support**.
- **Group Policy**, **OUs**, and **Kerberos authentication** are core features of AD.
- In hybrid scenarios, **Azure AD Connect** is used to sync AD identities to the cloud.

---