# 👑 Privileged Identity Management (PIM)

**Azure AD Privileged Identity Management (PIM)** helps you manage, monitor, and control access to **important roles and resources** in your organization.

It ensures that **privileged access is only granted when needed**, helping reduce the risk of over-permissioned users.

---

## 🎯 Why Use PIM?

- **Limit standing (always-on) admin access**
- Provide **just-in-time (JIT)** role activation
- Enforce **approval workflows** and **MFA**
- Generate **audit logs** and access history
- Automatically **expire unused assignments**

---

## 🔐 What Can You Manage with PIM?

| Resource Type               | Example |
|----------------------------|---------|
| **Azure AD roles**         | Global Admin, User Admin, Security Admin |
| **Azure resource roles**   | Owner, Contributor, Reader |
| **Groups (Microsoft Entra ID)** | Group owners and members |

---

## 🕒 Just-In-Time Access

Users can be **eligible** for roles instead of **permanently assigned**.  
They **activate** the role when needed, often with:

- MFA
- Approval
- Justification
- Time-bound access

| Term           | Meaning |
|----------------|---------|
| **Eligible**   | Can request activation when needed |
| **Active**     | Currently holds the role |
| **Permanent**  | Always has the role (not recommended) |

---

## 📋 Role Activation Process

1. User requests activation of a role
2. Optional: MFA, approval, and justification
3. Role is activated for a limited time
4. PIM logs the action for auditing

---

## 📈 Key Features

| Feature                      | Description |
|------------------------------|-------------|
| **JIT Activation**           | Reduces risk of misuse by limiting duration |
| **Approval workflows**       | Add extra verification before activation |
| **Audit logs**               | Track who activated what, and when |
| **Access reviews**           | Periodically review privileged assignments |
| **Notifications**            | Alerts for role assignments and activations |

---

## 🛡️ Security Benefits

- Reduces **risk from standing privileged access**
- Helps enforce **least privilege principle**
- Provides **transparency and accountability**

---

## 🔐 License Requirement

- Requires **Azure AD Premium P2**

---

## 📝 Exam Tips

- PIM is used for managing **just-in-time privileged access**.
- Roles can be assigned as **eligible** or **active**.
- Supports **approval, MFA, notifications, and audits**.
- Applies to **Azure AD roles**, **Azure RBAC roles**, and **groups**.
- You may be asked:  
  👉 *Which Azure feature allows users to activate privileged roles only when needed?*  
  ✅ Answer: **Privileged Identity Management (PIM)**

---