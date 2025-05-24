# ☁️ Azure Active Directory (Azure AD)

**Azure Active Directory (Azure AD)** is Microsoft’s **cloud-based identity and access management (IAM) service**. It helps your employees access external resources like Microsoft 365, the Azure portal, and thousands of other SaaS apps.

---

## 🧠 What is Azure AD?

Azure AD is a **modern cloud identity provider** that:

- Authenticates users and services
- Controls access to resources using **RBAC**, **Conditional Access**, and **MFA**
- Supports **Single Sign-On (SSO)** for both Microsoft and third-party apps
- Enables **B2B** and **B2C collaboration**

---

## 🔑 Key Features

| Feature                          | Description |
|----------------------------------|-------------|
| **Single Sign-On (SSO)**         | Sign in once to access multiple apps. |
| **Multi-Factor Authentication (MFA)** | Adds a second layer of security to user sign-ins. |
| **Conditional Access**           | Policies that allow or block access based on conditions like location, device, or risk. |
| **Self-service password reset (SSPR)** | Lets users reset passwords securely without IT help. |
| **Device registration**          | Devices can be Azure AD-registered or joined for identity-based access. |
| **Role-Based Access Control (RBAC)** | Restrict access to resources based on roles. |
| **Integration with on-prem AD**  | Using **Azure AD Connect** to create a hybrid identity. |

---

## 🔁 Azure AD vs Active Directory

| Feature                      | Azure AD                              | Active Directory (AD)               |
|-----------------------------|----------------------------------------|-------------------------------------|
| Type                        | Cloud-based                            | On-premises                         |
| Protocols                   | OAuth 2.0, OpenID Connect, SAML        | LDAP, Kerberos                      |
| Device Join                 | Azure AD Join / Registration           | Domain Join                         |
| App Support                 | Web, mobile, cloud apps                | Windows domain apps                 |
| Group Policy Support        | ❌ No                                   | ✅ Yes                               |
| Best For                    | Modern/cloud apps & remote access      | Traditional on-prem networks        |

---

## 🔄 Azure AD Editions

| Edition                | Key Features |
|------------------------|--------------|
| **Free**               | Basic identity features and SSO for 10 apps. |
| **Premium P1**         | Conditional Access, group-based access, self-service, dynamic groups. |
| **Premium P2**         | All P1 features + Identity Protection, Privileged Identity Management (PIM). |

---

## 🔐 Identity Types in Azure AD

| Identity Type         | Description |
|------------------------|-------------|
| **User**               | Represents a person in your org or an external guest. |
| **Group**              | A collection of users (static or dynamic). |
| **Service Principal**  | Identity used by apps/services to access Azure resources. |
| **Managed Identity**   | Special identity for Azure services to access other services securely. |

---

## 📝 Exam Tips

- Azure AD is the **cloud-based identity provider** in Microsoft’s ecosystem.
- Supports **SSO**, **MFA**, **Conditional Access**, and **RBAC**.
- Know the differences between **Azure AD** and **on-prem AD**.
- Be familiar with **P1 vs P2** licenses — especially that **P2 includes Identity Protection and PIM**.
- Understand that **Azure AD is used for authentication**, while **RBAC and policies handle authorization**.
- Expect scenario-based questions around **SSO**, **access control**, and **secure identity management**.

---