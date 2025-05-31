# 🧭 Azure Policy

**Azure Policy** is a **governance service** that helps you **enforce rules** and **standards** across your Azure environment.

It ensures resources stay **compliant** with your organization’s requirements by **allowing, auditing, or denying** actions based on policy definitions.

---

## 🎯 Purpose of Azure Policy

- Enforce **organizational standards**
- Ensure **resource compliance**
- Prevent **misconfigurations**
- Automatically **remediate non-compliant resources**

---

## 🧱 Key Components

| Component        | Description |
|------------------|-------------|
| **Policy Definition** | The rule or condition you want to enforce (e.g., disallow public IPs) |
| **Initiative (Policy Set)** | A group of policies bundled together |
| **Assignment**       | Applying a policy or initiative to a scope (subscription, resource group, etc.) |
| **Effect**           | What happens when a policy condition is met (e.g., Deny, Audit, Append, Modify) |

---

## 🔐 Common Policy Scenarios

- **Enforce specific VM sizes or regions**
- **Disallow untagged resources**
- **Require encryption on storage accounts**
- **Restrict public access to resources**
- **Audit usage of certain SKUs or features**

---

## 🧰 Use Cases

- Ensuring **compliance with internal standards**
- Implementing **regulatory frameworks** (ISO, NIST, etc.)
- **Controlling costs** by limiting resource types
- **Tag enforcement** for cost management and tracking

---

## 🧠 How It Works

1. Create a **policy definition** (or use a built-in one).
2. **Assign** it to a scope (management group, subscription, resource group).
3. Azure evaluates resources **continuously**.
4. **Non-compliant resources** are flagged or blocked.

---

## 📝 Exam Tips

- **Azure Policy** helps **enforce governance and compliance** across Azure resources.
- Use **policy definitions** to **audit, deny, or modify** deployments.
- **Initiatives** = multiple policies grouped for large-scale compliance.
- You may be asked:  
  👉 *Which Azure service allows you to enforce organizational standards across resources and automatically remediate non-compliant ones?*  
  ✅ Answer: **Azure Policy**

---