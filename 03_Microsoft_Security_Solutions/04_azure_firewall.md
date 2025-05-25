# 🔥 Azure Firewall

**Azure Firewall** is a **cloud-native, fully stateful firewall-as-a-service** that provides **network and application-level protection** for Azure Virtual Network (VNet) resources.

It allows you to **centrally control and log** all traffic flows using **built-in high availability and scalability**.

---

## 🎯 Purpose of Azure Firewall

- Protect Azure resources from **unwanted or malicious traffic**
- Enforce **centralized access policies** across VNets
- Filter **inbound, outbound, and lateral (east-west)** traffic

---

## 🛡️ Key Features

| Feature                        | Description |
|--------------------------------|-------------|
| **Stateful packet inspection** | Tracks connection state for intelligent filtering |
| **FQDN filtering**             | Allow/block access based on domain names |
| **Network traffic filtering**  | Allow/deny traffic based on IP, port, protocol |
| **Application rule filtering** | Inspect traffic based on HTTP/S, domain names |
| **Threat intelligence**        | Automatically block traffic from known malicious IPs |
| **Integration with Logs**      | Works with Azure Monitor and Sentinel for analytics |
| **High Availability**          | Built-in redundancy without load balancer |

---

## 🧱 Rule Types

| Rule Type           | Purpose |
|---------------------|---------|
| **Network Rules**   | IP-based (e.g., allow TCP from 10.0.0.1 to 10.0.0.2 on port 443) |
| **Application Rules**| Domain-based (e.g., allow access to `*.microsoft.com`) |
| **NAT Rules**       | Translate public IP to private IP (inbound DNAT) |

---

## 🌐 Deployment Options

| Mode             | Description |
|------------------|-------------|
| **Hub-and-Spoke**| Centralize security in a hub VNet with Azure Firewall |
| **Virtual WAN**  | Use Azure Firewall Manager for managing firewalls across multiple regions/networks |

---

## 🔐 Azure Firewall vs NSG vs Azure Firewall Premium

| Feature                   | NSG          | Azure Firewall (Standard) | Azure Firewall Premium |
|---------------------------|--------------|----------------------------|-------------------------|
| Layer                     | Network      | L3–L7 (Stateful)           | L3–L7 (with TLS inspection) |
| App Filtering             | ❌           | ✅                         | ✅                      |
| Threat Intelligence       | ❌           | ✅                         | ✅                      |
| TLS Inspection            | ❌           | ❌                         | ✅                      |
| IDPS (Intrusion Detection)| ❌           | ❌                         | ✅                      |

---

## 📝 Exam Tips

- **Azure Firewall** provides **centralized, stateful filtering** for VNets.
- Use it for **layer 3–7 filtering**, **FQDN-based rules**, and **application control**.
- Unlike NSGs, Azure Firewall can perform **deep inspection** and **threat detection**.
- **Azure Firewall Premium** adds **TLS inspection** and **IDPS**.
- You may be asked:  
  👉 *Which Azure service provides centralized, stateful, network and application layer protection?*  
  ✅ Answer: **Azure Firewall**

---