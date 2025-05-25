# 🔐 Azure Bastion

**Azure Bastion** is a **fully managed PaaS service** that provides **secure and seamless RDP/SSH access to Azure VMs** — **without exposing them to the public internet**.

It acts as a **jump server**, accessible through the **Azure portal**, helping you avoid using public IPs or opening inbound ports like 3389 or 22.

---

## 🎯 Purpose of Azure Bastion

- Enable **secure remote access** to Azure VMs
- Avoid exposing VMs to **internet-based threats**
- Remove the need for **public IP addresses**
- Simplify **administrative access** to internal VMs

---

## 🛡️ Key Benefits

| Benefit                     | Description |
|-----------------------------|-------------|
| **No Public IP Required**   | VM can stay on private IP only |
| **Browser-Based Access**    | Use RDP/SSH via Azure portal |
| **Fully Managed by Azure**  | No patching or setup required |
| **Increased Security**      | No need to open RDP/SSH ports on NSG |
| **Seamless Integration**    | Works natively with Azure networking |

---

## 🖥️ How It Works

1. You deploy **Azure Bastion** in a virtual network (VNet).
2. You access your VM through **Azure Portal** using Bastion.
3. The session is tunneled through **SSL (port 443)**.
4. The VM remains **isolated from direct internet access**.

---

## 🔐 Security Comparison

| Method         | Uses Public IP? | Exposes VM Ports? | Browser Access | Recommended? |
|----------------|------------------|--------------------|----------------|---------------|
| Traditional RDP/SSH | ✅ Yes       | ✅ Yes (3389/22)    | ❌ No          | ❌ No         |
| **Azure Bastion**   | ❌ No        | ❌ No               | ✅ Yes         | ✅ Yes        |

---

## 📋 Prerequisites

- Deploy in **same VNet** as your VM (or peered VNet)
- Subnet named `AzureBastionSubnet` (min /27)
- VM must have **network connectivity** to Bastion

---

## 🔐 Licensing

- **Hourly pricing** + **data transfer** cost  
- No additional license is needed — **pay-as-you-go**

---

## 📝 Exam Tips

- **Azure Bastion** provides **secure RDP/SSH access via browser**.
- Eliminates need for **public IPs** and **inbound NSG rules**.
- Helps protect VMs from **port scanning and brute-force attacks**.
- You may be asked:  
  👉 *Which Azure service allows RDP/SSH access to a VM without a public IP address?*  
  ✅ Answer: **Azure Bastion**

---