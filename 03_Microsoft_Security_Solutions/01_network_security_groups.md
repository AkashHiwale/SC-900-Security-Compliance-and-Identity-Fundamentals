# 🔐 Network Security Groups (NSGs)

A **Network Security Group (NSG)** in Azure is used to **control inbound and outbound network traffic** to resources in a **Virtual Network (VNet)**.

It acts as a **virtual firewall** for your Azure resources.

---

## 🎯 Purpose of NSGs

- **Allow or deny network traffic** to and from resources
- Control access at the **network level**
- Protect resources like **Virtual Machines, subnets, and NICs**

---

## 🧱 How NSGs Work

NSGs contain a list of **security rules** that are evaluated in **priority order**.

Each rule defines:

| Field         | Description |
|---------------|-------------|
| **Name**      | Rule identifier |
| **Priority**  | Lower number = higher priority |
| **Direction** | Inbound or Outbound |
| **Protocol**  | TCP, UDP, or * (all) |
| **Port**      | Specific port or range |
| **Source/Destination** | IP, CIDR block, tag (e.g., Internet, VirtualNetwork) |
| **Action**    | Allow or Deny |

---

## 📥 Inbound vs 📤 Outbound

| Direction  | Applies To |
|------------|------------|
| **Inbound**  | Traffic coming **into** a VM or resource |
| **Outbound** | Traffic **leaving** the VM or resource |

---

## 🔗 Where Can You Apply NSGs?

| Level          | Example |
|----------------|---------|
| **Subnet**      | Controls traffic to all VMs in the subnet |
| **Network Interface (NIC)** | Controls traffic for a specific VM only |

> 📝 If NSGs are applied at both levels, **NIC rules override subnet rules**.

---

## 🛡️ Default Rules (Always Present)

Azure adds **3 default rules** with low priority (high numbers):

| Rule Name               | Priority | Direction | Action | Description                      |
|-------------------------|----------|-----------|--------|----------------------------------|
| AllowVnetInBound        | 65000    | Inbound   | Allow  | Allow traffic within the VNet    |
| AllowAzureLoadBalancer  | 65001    | Inbound   | Allow  | Allow Azure Load Balancer traffic |
| DenyAllInbound / Outbound| 65500    | Both      | Deny   | Block all other traffic          |

> 🔄 Custom rules must have **priority 100–4096** and are evaluated before default rules.

---

## 🧪 Example Scenario

> 🚫 Block all inbound RDP (port 3389) to a VM:

```plaintext
Name: Deny-RDP
Priority: 100
Direction: Inbound
Port: 3389
Protocol: TCP
Source: Any
Destination: Any
Action: Deny
```

---

## 📝 Exam Tips

- **NSGs** are used to **filter network traffic** to/from Azure resources.
- Can be applied to **subnets** and **NICs**.
- Rules are processed in **priority order**, lower number wins.
- **Default rules** allow VNet traffic and deny all else.
- You may be asked:  
  👉 *Which Azure feature lets you control traffic flow at the network layer?*  
  ✅ Answer: **Network Security Group**

---