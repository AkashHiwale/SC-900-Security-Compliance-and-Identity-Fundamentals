# 🛡️ Identity-Based Attacks

**Identity-based attacks** target user credentials or identity systems to gain unauthorized access to systems, data, or services. These attacks exploit weak or stolen identities to bypass security and impersonate legitimate users.

---

## 🔑 Password-Based Attacks

Password attacks attempt to obtain or guess a user's password in order to gain access to their account or data.

### 🔁 Common Types

- **Brute Force Attack**  
  Repeatedly trying all possible combinations of characters to crack a password.

- **Dictionary Attack**  
  Attempts passwords using a precompiled list of commonly used or known passwords.

- **Credential Stuffing**  
  Using credentials obtained from data breaches to access other accounts where users may have reused the same passwords.

- **Password Spraying**  
  Tries one commonly used password (like `P@ssw0rd`) across many accounts to avoid lockouts.

### 🚫 Risks
- Weak or reused passwords make users highly vulnerable.
- Accounts may be compromised without users realizing it.

---

## 🎣 Phishing Scams

Phishing is a form of **social engineering** where attackers impersonate a trusted source to trick users into revealing sensitive information such as passwords, MFA codes, or credit card details.

### 🧪 Common Types

- **Email Phishing**  
  A fraudulent email appears to be from a legitimate source (e.g., Microsoft, HR, IT support).

- **Spear Phishing**  
  A targeted attack aimed at a specific individual or organization using personalized details.

- **Smishing**  
  Phishing through SMS or text messages.

- **Vishing**  
  Voice phishing where attackers pretend to be someone trustworthy over the phone.

### ⚠️ Impact
- Compromise of credentials
- Financial loss
- Lateral movement within the organization

---

## 🛡️ Defenses Against Identity-Based Attacks

| Defense Mechanism           | Description |
|-----------------------------|-------------|
| **Multi-Factor Authentication (MFA)** | Adds an extra layer of verification beyond passwords. |
| **Password Protection**     | Enforce strong, complex password policies; use banned password lists. |
| **Azure AD Smart Lockout**  | Detects and blocks brute force attempts automatically. |
| **Azure AD Identity Protection** | Detects risky sign-ins and enforces automated responses. |
| **Conditional Access**      | Allows access only when certain conditions are met (location, device state, etc.). |
| **Security Awareness Training** | Educate users to recognize phishing and social engineering attacks. |

---

## 📝 Exam Tips

- Understand how **password attacks** (like brute force and dictionary attacks) work and how to defend against them using **Azure AD password protection**.
- **Phishing scams** are social engineering techniques — recognize the types: email phishing, spear phishing, smishing, and vishing.
- **MFA is one of the most effective defenses** against identity-based attacks.
- **Azure AD Identity Protection** helps detect and respond to risky sign-in behaviors.
- You may see questions that ask which Azure service helps protect against stolen credentials or risky logins (hint: **Azure AD Identity Protection**).
- Be familiar with **Conditional Access** and its role in reducing the attack surface for compromised identities.

---