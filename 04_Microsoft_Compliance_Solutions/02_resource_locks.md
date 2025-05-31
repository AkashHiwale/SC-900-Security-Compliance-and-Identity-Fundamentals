# 🔒 Azure Resource Locks

**Azure Resource Locks** help prevent **accidental deletion or modification** of your Azure resources.

They are a simple way to enforce **resource protection**, even for users with high-level permissions like **Owner**.

---

## 🎯 Purpose of Resource Locks

- Protect critical resources from accidental or unauthorized changes
- Enforce operational safety for production systems
- Add an extra layer of security beyond Role-Based Access Control (RBAC)

---

## 🔐 Lock Levels

| Lock Type      | Description                                      | Effect |
|----------------|--------------------------------------------------|--------|
| `ReadOnly`     | Allows reading the resource but **no changes**   | Cannot update or delete |
| `CanNotDelete` | Allows read and modify, but **cannot delete**    | Resource is safe from deletion |

---

## 🧠 How It Works

- You **apply a lock** at the **subscription**, **resource group**, or **resource** level.
- Locks **inherit down** the resource hierarchy.
- Even users with **Owner** or **Contributor** roles **cannot override** a lock without removing it.

---

## ⚙️ Example Use Cases

- Preventing deletion of a **critical VM or database**
- Locking a **production resource group** to avoid accidental changes
- Applying a `ReadOnly` lock to **audit-sensitive logs or storage**

---

## 🔁 Lock Scope

| Scope             | Description |
|------------------|-------------|
| **Subscription**  | Applies to all resources within the subscription |
| **Resource Group**| Applies to all resources within the group |
| **Individual Resource** | Applies only to the selected resource |

---

## ⚠️ Important Notes

- Locks can only be removed by someone with **appropriate access (Owner or User Access Administrator)**.
- **Automation scripts** or **Terraform** deployments can fail if locked resources are involved.

---

## 📝 Exam Tips

- **Resource Locks** are used to **prevent accidental deletion or modification**.
- Two types: `ReadOnly` and `CanNotDelete`.
- Can be applied at **resource, resource group, or subscription** level.
- You may be asked:  
  👉 *Which Azure feature prevents accidental deletion of critical resources?*  
  ✅ Answer: **Azure Resource Locks**

---