# 🛡️ Security Defaults in Azure AD

**Security Defaults** are **pre-configured identity security settings** in Azure Active Directory designed to help protect your organization from common identity-related attacks.

They are **enabled by default** for all new tenants and provide **basic, strong protection** without requiring complex configurations.

---

## 🎯 Purpose of Security Defaults

Security defaults are designed to:

- Protect against **common identity attacks** like phishing, password spray, and credential stuffing.
- Promote the use of **MFA (Multi-Factor Authentication)**.
- Provide a **secure baseline** for all organizations, especially those without dedicated security teams.

---

## 🧰 What Does Security Defaults Enable?

| Feature Enabled                      | Description |
|-------------------------------------|-------------|
| **Require all users to register for MFA** | Users must set up MFA with Microsoft Authenticator. |
| **Require MFA for admins**           | MFA is enforced for privileged roles like Global Admin, Security Admin, etc. |
| **Block legacy authentication**      | Older protocols like POP, IMAP, SMTP AUTH are blocked as they don’t support MFA. |
| **Protect privileged actions**       | Users performing risky actions must reauthenticate or use MFA. |

---

## 🆚 Security Defaults vs Conditional Access

| Feature                      | Security Defaults            | Conditional Access             |
|------------------------------|-------------------------------|---------------------------------|
| **Complexity**               | Simple, one-click enable     | Highly customizable             |
| **Best For**                 | Small to medium organizations | Enterprises with specific needs |
| **Customization**            | ❌ Not customizable           | ✅ Fully customizable            |
| **License Required**         | ❌ No (Free tier)             | ✅ Yes (Azure AD Premium P1/P2) |

---

## 🚦 Who Gets Security Defaults?

- **All new Azure AD tenants** have Security Defaults **enabled by default**.
- **Admins** can enable/disable them manually in Azure AD > Properties > Manage Security Defaults.

---

## 🚨 Important Notes

- Enabling **Conditional Access** **automatically disables Security Defaults**.
- Security Defaults are **mutually exclusive** with Conditional Access policies.

---

## 📝 Exam Tips

- Security Defaults are **free**, **pre-configured**, and meant to **improve security posture** quickly.
- Focuses on **enabling MFA**, **blocking legacy auth**, and **securing admin accounts**.
- Good for orgs that don’t have resources to build complex security policies.
- You may be asked:  
  👉 *Which Azure AD feature provides built-in identity security with no extra license?*  
  ✅ Answer: **Security Defaults**

---