# 🔐 Multi-Factor Authentication (MFA)

**Multi-Factor Authentication (MFA)** is a security feature that adds an **extra layer of protection** on top of a username and password.

It helps prevent unauthorized access, even if a password is compromised.

---

## 🧠 What is MFA?

MFA requires users to **verify their identity using at least two of the following**:

| Factor Type          | Example                      |
|----------------------|------------------------------|
| **Something you know** | Password, PIN                |
| **Something you have** | Phone, hardware token        |
| **Something you are**  | Fingerprint, facial recognition |

---

## ✅ Why Use MFA?

- **Over 99%** of identity attacks can be blocked by MFA.
- Passwords alone are **not enough** to secure identities.
- Common attacks like **phishing**, **password spray**, and **credential stuffing** often rely on compromised passwords.

---

## 📲 MFA Methods in Azure AD

| Method                     | Description |
|----------------------------|-------------|
| **Microsoft Authenticator** | App for push notifications and codes. |
| **SMS-based verification**  | One-time code sent via text. |
| **Voice call verification** | Code or approval via phone call. |
| **Hardware tokens (OATH)**  | Physical devices generating time-based codes. |

---

## ⚙️ Where is MFA Used?

| Scenario                             | Description |
|--------------------------------------|-------------|
| **Sign-in to Azure Portal**          | MFA can be enforced for admins or all users. |
| **Conditional Access policies**      | MFA can be required only under certain conditions (e.g., high risk sign-in, unknown location). |
| **Security Defaults**                | Automatically enforces MFA for all users. |
| **Self-Service Password Reset (SSPR)** | May require MFA for verification. |

---

## 🔐 MFA vs Two-Factor Authentication (2FA)

> 📌 **2FA** = Always two factors.  
> 📌 **MFA** = Two or more factors.

MFA is a **broader** term — it includes 2FA but allows for **multiple** combinations of factors.

---

## 📝 Exam Tips

- MFA significantly reduces the chances of unauthorized access.
- Azure AD supports **MFA via Security Defaults**, **Conditional Access**, or **per-user MFA settings**.
- **Security Defaults** automatically require users to register for MFA.
- You may see questions like:  
  👉 *Which feature adds another layer of identity protection beyond passwords?*  
  ✅ Answer: **Multi-Factor Authentication**

---