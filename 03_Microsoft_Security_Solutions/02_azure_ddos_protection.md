# 🌐 Azure DDoS Protection

**Azure Distributed Denial of Service (DDoS) Protection** helps protect your applications and resources from large-scale **DDoS attacks** that attempt to overwhelm services and cause outages.

Azure DDoS Protection provides **always-on traffic monitoring** and **automatic attack mitigation**.

---

## 🎯 Purpose of DDoS Protection

- Prevent service disruptions caused by **malicious traffic floods**
- Automatically detect and mitigate **volumetric, protocol, and resource layer attacks**
- Enhance security for **public-facing endpoints**

---

## 🛡️ Two Tiers of DDoS Protection

| Tier                  | Description |
|-----------------------|-------------|
| **Basic (Default)**   | Free and automatically enabled for every Azure service using public IP. Protects Microsoft infrastructure. |
| **Standard (Paid)**   | Advanced protection for your own apps/resources with detailed telemetry, alerts, and cost protection. |

---

## 🔍 Features of DDoS Protection Standard

| Feature                         | Description |
|----------------------------------|-------------|
| **Automatic attack detection**   | Real-time monitoring and mitigation without user intervention |
| **Adaptive tuning**              | Learns normal traffic patterns and detects anomalies |
| **Mitigation policies**          | Automatically blocks malicious traffic while allowing legitimate traffic |
| **Metrics & Logging**            | Integration with Azure Monitor, Logs, Alerts |
| **Cost Protection**              | Provides service credits for attack-related scale-out costs |
| **DDoS Rapid Response (DRR)**    | Microsoft support available during an active attack |

---

## 🧠 Types of Attacks Mitigated

| Type                  | Example |
|-----------------------|---------|
| **Volumetric Attacks**| Flood of traffic to exhaust bandwidth |
| **Protocol Attacks**  | Exploiting protocol flaws (e.g., SYN floods) |
| **Resource Attacks**  | Target app or service to exhaust compute/memory resources |

---

## ✅ Ideal Usage

Use **DDoS Protection Standard** when:

- You host **publicly accessible services** (e.g., web apps, APIs)
- You need **guaranteed protection + insights** into attacks
- You require **regulatory compliance or SLAs**

> 🔄 Can be enabled at the **virtual network (VNet)** level and protects all public IPs in that VNet.

---

## 💰 Licensing

| Plan         | Included |
|--------------|----------|
| **Basic**    | Free (default for all Azure services) |
| **Standard** | Paid add-on (per VNet), includes support + insights |

---

## 📝 Exam Tips

- **Azure DDoS Protection** defends against **large-scale external attacks**.
- **Standard tier** offers **adaptive, automatic mitigation** and telemetry.
- **Basic tier** is included by default for Azure services but has **limited visibility**.
- You may be asked:  
  👉 *Which Azure service protects against large-scale traffic floods targeting public endpoints?*  
  ✅ Answer: **Azure DDoS Protection**

---