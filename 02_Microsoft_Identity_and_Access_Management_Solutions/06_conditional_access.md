# 🎯 Conditional Access

**Conditional Access** is a powerful Azure AD feature that allows you to **enforce access controls** based on conditions.  
It helps strike a balance between **security** and **user productivity**.

---

## 🧠 What is Conditional Access?

Conditional Access (CA) uses **if-then logic**:

> **If** a user signs in under specific conditions,  
> **Then** enforce specific controls.

Example:  
> If a user signs in from an unknown location → require **Multi-Factor Authentication (MFA)**.

---

## 🛠️ How It Works

Conditional Access policies are triggered **after the first factor of authentication** and before access is granted.

| Step | Action |
|------|--------|
| 1️⃣   | User enters username and password |
| 2️⃣   | CA policies evaluate the sign-in context |
| 3️⃣   | Access is either granted, denied, or more verification is required |

---

## 🧩 Common Conditions

| Condition Type             | Examples |
|----------------------------|----------|
| **User or group**          | Apply to specific users, groups, or roles |
| **Location**               | Known/trusted vs unknown IPs or countries |
| **Device state**           | Compliant, domain joined, or hybrid joined |
| **Sign-in risk**           | Low, medium, high (requires Identity Protection) |
| **Application**            | Microsoft 365, Azure portal, custom apps |

---

## 🔐 Common Access Controls

| Control Type                | Description |
|-----------------------------|-------------|
| **Require MFA**             | Most common control |
| **Block access**            | Deny access entirely |
| **Grant access with conditions** | Allow access but enforce conditions (e.g., MFA or compliant device) |
| **Session controls**        | Limit session duration, restrict download, etc. (mostly for browser-based apps) |

---

## 🧪 Example Scenarios

| Scenario | Conditional Access Action |
|----------|---------------------------|
| User signs in from unknown country | Block or require MFA |
| Admin signs in to Azure portal | Always require MFA |
| Sign-in from unmanaged device | Allow access only if device is compliant |

---

## 🔁 Conditional Access vs Security Defaults

| Feature                | Security Defaults         | Conditional Access             |
|------------------------|----------------------------|---------------------------------|
| **Customization**      | ❌ No                      | ✅ Yes                         |
| **Targeted policies**  | ❌ One-size-fits-all       | ✅ Per user, group, or app     |
| **License required**   | ❌ Free                    | ✅ Azure AD Premium P1+        |
| **Best for**           | Small orgs or quick setup | Medium to large orgs with specific needs |

> ⚠️ **Note**: Enabling Conditional Access disables **Security Defaults**.

---

## 📝 Exam Tips

- **Conditional Access** lets you control **how and when users access cloud resources**.
- Works **after the user signs in** but **before access is granted**.
- Common controls include **require MFA**, **block access**, and **require compliant device**.
- Requires **Azure AD Premium P1 or P2**.
- Expect scenario-based questions like:  
  👉 *A user signs in from a risky location. What feature can require MFA or block access?*  
  ✅ Answer: **Conditional Access**

---