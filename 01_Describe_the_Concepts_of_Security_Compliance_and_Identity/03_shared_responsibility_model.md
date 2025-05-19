# 🤝 Shared Responsibility Model

The **Shared Responsibility Model** defines the division of security responsibilities between the **cloud provider** (e.g., Microsoft Azure) and the **customer** (you or your organization).

Understanding this model helps determine **who is responsible for securing what** in different cloud service models such as IaaS, PaaS, and SaaS.

---

## 🧠 Key Concept

- **Cloud security is a shared responsibility.**
- The responsibilities vary based on the **type of cloud service** used:
  - **IaaS (Infrastructure as a Service)**
  - **PaaS (Platform as a Service)**
  - **SaaS (Software as a Service)**

---

## 🔄 Division of Responsibilities Across Cloud Models

The **level of customer responsibility** decreases as you move from **IaaS → PaaS → SaaS**, while the **cloud provider (Microsoft)** takes on more.

| Responsibility                  | IaaS (Infra as a Service) | PaaS (Platform as a Service) | SaaS (Software as a Service) |
|----------------------------------|----------------------------|-------------------------------|-------------------------------|
| **Physical security (data centers)** | ✅ Microsoft                  | ✅ Microsoft                   | ✅ Microsoft                   |
| **Network infrastructure**           | ✅ Microsoft                  | ✅ Microsoft                   | ✅ Microsoft                   |
| **Host infrastructure**              | ✅ Microsoft                  | ✅ Microsoft                   | ✅ Microsoft                   |
| **Virtualization / Hypervisor**      | ✅ Microsoft                  | ✅ Microsoft                   | ✅ Microsoft                   |
| **Guest OS**                         | 🔒 Customer                   | ✅ Microsoft                   | ✅ Microsoft                   |
| **Middleware / Runtime**            | 🔒 Customer                   | ✅ Microsoft                   | ✅ Microsoft                   |
| **Application**                     | 🔒 Customer                   | 🔒 Customer                    | ✅ Microsoft                   |
| **Data**                             | 🔒 Customer                   | 🔒 Customer                    | 🔒 Customer                    |
| **Identity & Access Management**     | 🔒 Customer                   | 🔒 Customer                    | 🔒 Customer                    |
| **Data classification & governance** | 🔒 Customer                   | 🔒 Customer                    | 🔒 Customer                    |
| **Endpoint protection**              | 🔒 Customer                   | 🔒 Customer                    | 🔒 Customer                    |

✅ = Responsibility of **Microsoft**  
🔒 = Responsibility of **Customer**

---

## ☁️ Examples by Cloud Model

### IaaS (e.g., Azure VMs)
- **Customer** manages: OS patches, endpoint security, identity, app logic
- **Microsoft** manages: physical hosts, network, data center, hypervisor

### PaaS (e.g., Azure App Service)
- **Customer** manages: application code, identity, and data
- **Microsoft** manages: OS, runtime, middleware, infrastructure

### SaaS (e.g., Microsoft 365)
- **Customer** manages: identity, access control, and data
- **Microsoft** manages: everything else (app, OS, infrastructure)

---

## 🎯 Why it Matters

Misunderstanding the Shared Responsibility Model can lead to **security gaps**, such as:
- Unpatched VMs in IaaS
- Misconfigured access controls in SaaS apps
- Data breaches due to weak identity management

---

## 📝 Exam Tips

- The Shared Responsibility Model outlines which **security tasks are handled by Microsoft** and which are the **customer’s responsibility**.
- Microsoft is always responsible for: **physical security, networking, and the underlying cloud infrastructure**.
- The customer is always responsible for: **data, identities, devices, and access management**.
- The more managed the service (IaaS → PaaS → SaaS), the **less** the customer needs to manage directly.
- Expect questions that ask you to identify responsibilities under different service models (IaaS vs. PaaS vs. SaaS).

---