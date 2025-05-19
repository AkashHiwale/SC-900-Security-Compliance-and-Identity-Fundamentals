# 🔐 Secure Data

Data security is a critical component of cloud security. Microsoft Azure provides various tools and techniques to **protect data in transit, at rest, and during processing** using encryption and access controls.

---

## 🔒 What is Data Encryption?

**Encryption** is the process of converting data into an unreadable format using cryptographic algorithms to prevent unauthorized access. Only authorized parties can decrypt the data using appropriate keys.

---

## 🧪 Types of Encryption

### 🔁 Symmetric Encryption

- Uses **one single key** for both encryption and decryption.
- Faster and suitable for large amounts of data.
- Requires secure key exchange.

#### 🔑 Example:
- AES (Advanced Encryption Standard)

### 🔁 Asymmetric Encryption

- Uses a **pair of keys**: a **public key** (to encrypt) and a **private key** (to decrypt).
- More secure but slower than symmetric encryption.
- Commonly used in secure communications.

#### 🔑 Example:
- RSA (Rivest-Shamir-Adleman)

---

## 💾 Encryption at Rest

**Data at rest** refers to data stored on physical or virtual media (e.g., databases, disks, backups).

### 🔐 How it's secured:
- Encrypted using symmetric keys (e.g., AES-256).
- Azure uses **Storage Service Encryption (SSE)** by default.
- Integration with **Azure Key Vault** allows customer-managed keys (CMK).

### 🔧 Example Services:
- Azure Blob Storage, Azure SQL Database, Azure Managed Disks

---

## 🌐 Encryption in Transit

**Data in transit** refers to data actively moving from one location to another (e.g., over the internet or internal networks).

### 🔐 How it's secured:
- Encrypted using TLS (Transport Layer Security).
- Asymmetric encryption is often used to exchange session keys securely.

### 🔧 Example:
- HTTPS communication
- TLS-enabled Azure services

---

## 📦 Other Data Protection Techniques

- **Azure Information Protection (AIP)** – Classifies and labels sensitive data.
- **Microsoft Purview Data Loss Prevention (DLP)** – Monitors and controls sensitive data sharing.
- **Azure Key Vault** – Stores encryption keys, secrets, and certificates securely.
- **Customer-Managed Keys (CMK)** – Enables customers to control their own encryption keys.

---

## 📝 Exam Tips

- Symmetric encryption uses the same key for encryption and decryption (e.g., AES).
- Asymmetric encryption uses a public-private key pair (e.g., RSA).
- Encryption at rest protects stored data; Azure enables this by default using Storage Service Encryption.
- Encryption in transit protects data moving between systems and uses TLS protocols.
- Azure Key Vault is used to manage and store cryptographic keys and secrets.
- Know the difference between **service-managed keys** and **customer-managed keys** in Azure.
- You may be asked to identify which Microsoft services protect **data at rest**, **in transit**, or both.

---