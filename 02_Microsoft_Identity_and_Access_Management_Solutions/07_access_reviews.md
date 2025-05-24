# 🔎 Access Reviews in Azure AD

**Access Reviews** help organizations ensure that **only the right people have access** to specific resources such as **groups, applications, and roles**.

They are part of **Azure AD Identity Governance** and help maintain **least-privilege access**.

---

## 🎯 Purpose of Access Reviews

Access Reviews allow organizations to:

- **Audit and manage user access** to resources.
- **Detect and remove unnecessary or outdated access**.
- **Reduce risk** from excessive or unused permissions.

---

## 📌 Where Are Access Reviews Used?

| Area                         | Example |
|------------------------------|---------|
| **Microsoft 365 Groups / Teams** | Review group memberships periodically. |
| **Enterprise Applications**  | Review who has access to SaaS apps like Salesforce. |
| **Azure AD Roles**           | Ensure only authorized users have privileged roles (e.g., Global Admin). |

---

## 👤 Who Can Review Access?

- **Group owners**
- **Managers**
- **Selected reviewers**
- **Self-review (users review their own access)**

Admins can **assign reviewers** when creating the review.

---

## 🔁 Review Outcomes

Each reviewer can take actions like:

| Action          | Result |
|-----------------|--------|
| ✅ **Approve**   | Keep access |
| ❌ **Deny**      | Remove access |
| ⏸️ **Don't know** | No decision made |
| ⏱️ **Auto-apply results** | Remove access after deadline if no response |

---

## ⚙️ Key Features

| Feature                       | Description |
|-------------------------------|-------------|
| **Automated reviews**         | Schedule recurring reviews monthly/quarterly. |
| **Recommendations**           | System suggests decisions (e.g., based on sign-in activity). |
| **Auto-removal**              | Inactive users can be automatically removed. |
| **Audit logs**                | Review history and decisions are logged for compliance. |

---

## 📝 Exam Tips

- **Access Reviews** help organizations ensure **only necessary access is retained**.
- Used for groups, enterprise apps, and Azure AD role assignments.
- Can be manual or **automated and recurring**.
- Part of **Azure AD Premium P2**.
- Reviewers can be **group owners**, **managers**, or **selected users**.
- You may be asked:  
  👉 *Which feature allows you to periodically validate user access to apps and groups?*  
  ✅ Answer: **Access Reviews**

---