# 🛡️ Common Security Threats

This section provides an overview of **common cybersecurity threats** that organizations and individuals face. Understanding these threats is key to implementing effective security strategies.

---

## 📖 1. Dictionary Attack

### 🔍 What is it?
A **dictionary attack** is a brute-force technique where an attacker systematically tries a list of common words, phrases, or passwords (a "dictionary") to guess login credentials.

### ⚙️ How it works:
- The attacker uses precompiled lists of commonly used passwords.
- Each word from the list is tested against a login system.
- If a match is found, access is granted.

### 🧪 Example Scenario:
```plaintext
Username: admin  
Password list: admin123, welcome1, password, letmein, 123456  
Result: System matches "admin123" and grants access.
```

### 🛡️ Prevention:
- Enforce **complex password policies**.
- Implement **account lockouts** after failed attempts.
- Use **multi-factor authentication (MFA)**.
- Monitor for **unusual login activity**.

---

## 🦠 2. Ransomware

### 🔍 What is it?
**Ransomware** is a type of malware that **encrypts files** on a device or network and demands a ransom from the victim to restore access.

### ⚙️ How it works:
- Spread via phishing emails, malicious links, or compromised software.
- Once installed, it encrypts data and displays a ransom demand.
- Payment is typically requested in cryptocurrency.

### 🧪 Example Scenario:
> A user opens a fake invoice email attachment.  
> Files are locked and a message appears:  
> _"Your files have been encrypted. Pay 1 Bitcoin to unlock."_

### 🛡️ Prevention:
- Regularly **backup data** and store it securely.
- Use **updated antivirus/antimalware tools**.
- Educate users on **phishing awareness**.
- Apply **security patches** and updates promptly.

---

## 🌐 3. Distributed Denial of Service (DDoS) Attack

### 🔍 What is it?
A **DDoS attack** floods a network, server, or website with excessive traffic from multiple sources, causing disruption or downtime.

### ⚙️ How it works:
- Attackers use a **botnet** (network of infected devices).
- All bots send requests to the target simultaneously.
- The system becomes overwhelmed and unresponsive.

### 🧪 Example Scenario:
> A retail website is hit with 1 million fake requests per second during a sale.  
> Genuine customers cannot access the site.

### 🛡️ Prevention:
- Use **Web Application Firewalls (WAF)**.
- Implement **rate limiting and traffic filtering**.
- Leverage **DDoS protection services** like **Azure DDoS Protection**.
- Monitor traffic with **network anomaly detection tools**.


---

## ✅ Summary Table

| Threat Type           | Target             | Attack Vector             | Impact                      | Prevention                                   |
|-----------------------|--------------------|----------------------------|-----------------------------|----------------------------------------------|
| Dictionary Attack     | User accounts      | Weak passwords             | Unauthorized access         | Strong passwords, MFA, account lockout       |
| Ransomware            | Files & systems    | Email, websites, software | Data encryption & ransom    | Backups, endpoint security, user awareness   |
| DDoS Attack           | Websites, networks | Botnet, infected devices   | Service disruption          | WAF, rate limiting, cloud DDoS protection    |

---

