# 🛡️ Defense in Depth

**Defense in Depth** is a cybersecurity strategy that uses multiple layers of defense to protect systems and data from attacks. The goal is to ensure that if one layer is compromised, others still provide protection.

---

## 🧱 What is Defense in Depth?

Defense in Depth is a **multi-layered approach** where security controls are implemented at various points in the IT environment. This slows down or stops attackers and limits the impact of a breach.

Each layer offers a specific function and builds redundancy into the system’s protection mechanisms.

---

## 🧩 Key Security Layers

| Layer                        | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Physical Security**        | Secures physical access to data centers, offices, and devices               |
| **Perimeter Security**       | Firewalls, DDoS protection, and VPNs to secure the network edge             |
| **Network Security**         | Network segmentation, NSGs, and threat detection systems                    |
| **Endpoint Security**        | Antivirus, EDR (e.g., Microsoft Defender for Endpoint) on user devices      |
| **Application Security**     | Controls at the app level: input validation, authentication, WAF            |
| **Data Security**            | Data encryption, classification, and loss prevention                       |
| **Identity and Access Control** | MFA, Conditional Access, RBAC to restrict access to resources              |
| **Monitoring and Response**  | SIEM systems like Microsoft Sentinel for detecting and responding to threats|

---

## 🔄 Visual Representation

```
+-----------------------------+
|     Monitoring & Response   | ← Microsoft Sentinel, Defender XDR
+-----------------------------+
| Identity & Access Control   | ← Entra ID, MFA, Conditional Access
+-----------------------------+
|        Data Security        | ← Encryption, Microsoft Purview DLP
+-----------------------------+
|     Application Security    | ← App Gateway WAF, Input validation
+-----------------------------+
|      Endpoint Security      | ← Defender for Endpoint
+-----------------------------+
|       Network Security      | ← NSGs, Azure Firewall, VPN
+-----------------------------+
|      Perimeter Security     | ← DDoS Protection, Azure Front Door
+-----------------------------+
|      Physical Security      | ← Data center access control
+-----------------------------+
```

---

## 📝 Exam Tips

- Defense in Depth is a layered security model used to mitigate threats at multiple levels.
- Understand how Microsoft solutions align with each layer:
  - Azure DDoS Protection → Perimeter Security
  - Network Security Groups (NSG) → Network Security
  - Microsoft Defender for Endpoint → Endpoint Security
  - Azure Application Gateway (WAF) → Application Security
  - Microsoft Purview Information Protection / DLP → Data Security
  - Microsoft Entra ID + MFA → Identity and Access Control
  - Microsoft Sentinel → Monitoring and Response
- The exam may test your ability to **match security services with their corresponding layers**.
- This concept supports the broader Zero Trust architecture.

---