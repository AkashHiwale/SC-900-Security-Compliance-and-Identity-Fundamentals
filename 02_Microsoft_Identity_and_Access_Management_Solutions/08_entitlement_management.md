# 🗂️ Entitlement Management in Azure AD

**Entitlement Management** is a feature of **Azure AD Identity Governance** that allows organizations to manage **access packages**—collections of resources users can request access to.

It helps automate and secure access to **apps, groups, and SharePoint sites** for **employees, guests, and external users**.

---

## 🎯 Purpose of Entitlement Management

- **Automate user access requests and approvals**.
- Provide **time-bound access** to resources.
- Ensure access is **reviewed and removed automatically**.
- Support **business-to-business (B2B)** collaboration.

---

## 📦 What is an Access Package?

An **Access Package** is a bundle of access permissions (apps, groups, roles) users can **request** through a **catalog**.

| Access Package Contains        | Examples |
|-------------------------------|----------|
| **Groups / Teams**            | Microsoft 365 Groups or Teams |
| **Applications**              | SaaS apps like Salesforce, Dropbox |
| **SharePoint Online sites**   | Internal documentation, project portals |
| **Azure AD roles (optional)** | e.g., Reader, Contributor |

---

## 🔁 Access Lifecycle

1. **User requests access**
2. **Approval workflow triggers** (can be manager or selected approver)
3. **Access is granted**
4. **Access expires or is reviewed**
5. **Access is removed automatically** if not renewed

---

## 🌍 External Access

Entitlement Management supports **B2B collaboration**:
- External users can request access.
- They are automatically invited to the directory.
- Their access is **reviewed and time-limited**.

---

## 🧰 Key Features

| Feature                   | Description |
|---------------------------|-------------|
| **Access packages**       | Bundle of resources users can request access to |
| **Approval workflows**    | One or multi-stage approval processes |
| **Expiration and renewal**| Time-limited access with renewal options |
| **Access reviews**        | Ensure continued justification for access |
| **Auto-removal**          | Access is revoked after expiration or review failure |

---

## 🔐 License Requirement

- Requires **Azure AD Premium P2**.

---

## 📝 Exam Tips

- **Entitlement Management** is used to **automate access governance**.
- Used to **bundle resources** into **access packages**.
- Enables **external (B2B) users** to safely request access.
- Works with **Access Reviews** and **approval workflows**.
- You may be asked:  
  👉 *Which Azure AD feature allows bundling of group/app access and automating the request/approval process?*  
  ✅ Answer: **Entitlement Management**

---