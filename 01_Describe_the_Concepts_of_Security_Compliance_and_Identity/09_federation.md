# 🌐 Federation

**Federation** is an identity relationship between two trusted identity systems that allows users to access systems and applications across organizational boundaries without needing to maintain separate credentials.

---

## 🔑 What is Federation?

Federation enables **Single Sign-On (SSO)** between organizations by establishing **trust** between an **identity provider (IdP)** and a **service provider (SP)**. Users authenticate with their own organization’s identity system, and that trusted identity is shared with external apps or services.

---

## 🧱 Key Concepts

| Term                 | Description |
|----------------------|-------------|
| **Identity Provider (IdP)**   | The system that authenticates the user (e.g., Azure AD, ADFS). |
| **Service Provider (SP)**     | The app or system that relies on the identity info (e.g., Salesforce, AWS). |
| **Trust Relationship**        | A secure configuration that allows the IdP and SP to trust one another. |
| **Claims**                    | Pieces of user info (like email, name, roles) passed from IdP to SP after authentication. |

---

## 🧰 Common Federation Protocols

| Protocol           | Description |
|--------------------|-------------|
| **SAML (Security Assertion Markup Language)** | XML-based standard for exchanging authentication and authorization data. |
| **WS-Federation**  | Protocol supported by ADFS for older applications. |
| **OAuth 2.0 / OpenID Connect** | Modern protocols used for federated authentication with web and cloud apps. |

---

## 🏢 Real-World Scenarios

- Allowing users in **Company A** to access **Company B’s** app using their existing credentials.
- Signing in to **third-party SaaS apps (like Salesforce, ServiceNow)** using **Azure AD**.
- Supporting **business-to-business (B2B)** access without duplicating user accounts.

---

## ☁️ Federation with Azure AD

Azure AD supports federation with:

- **ADFS (Active Directory Federation Services)**  
  To enable hybrid identity or legacy app support.

- **Third-party IdPs** (like Okta, Ping Identity)  
  Through SAML or OpenID Connect.

- **External organizations (B2B collaboration)**  
  Via **Azure AD B2B**, allowing external users to sign in using their own credentials.

---

## 📝 Exam Tips

- Federation enables **SSO across organizations** using **trusted identity providers**.
- Know the difference between **authentication (who you are)** and **federation (trusted identity sharing)**.
- Be familiar with common protocols: **SAML**, **OAuth 2.0**, **OpenID Connect**.
- **Azure AD supports federation** with both **on-prem (ADFS)** and **external IdPs**.
- Federation is key for **hybrid identity** and **partner collaboration** scenarios.

---