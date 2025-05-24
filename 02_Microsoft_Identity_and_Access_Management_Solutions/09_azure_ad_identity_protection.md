# 🛡️ Azure AD Identity Protection

**Azure AD Identity Protection** is a feature that helps organizations **detect, investigate, and respond to identity-based risks**.  
It uses signals and machine learning to identify **suspicious user activities and sign-ins**.

---

## 🎯 Purpose of Identity Protection

- Identify **vulnerabilities and risks** related to user identities.
- Automate **risk-based policies** like requiring MFA or blocking access.
- Help **secure access** to applications and services in real-time.

---

## 🔍 What Can It Detect?

| Risk Type          | Examples |
|--------------------|----------|
| **User Risk**       | Leaked credentials, suspicious user behavior |
| **Sign-in Risk**    | Impossible travel, unfamiliar location, infected devices |
| **Risky Users / Sign-ins** | Combined detection of threat intelligence + behavior anomalies |

---

## ⚙️ Key Capabilities

| Feature                     | Description |
|-----------------------------|-------------|
| **User Risk Detection**     | Identifies users likely compromised (e.g., leaked credentials). |
| **Sign-in Risk Detection**  | Flags unusual sign-in patterns (e.g., new IP, anonymous proxy). |
| **Risk Policies**           | Automate responses like requiring MFA or blocking access. |
| **Reports & Alerts**        | View risky users and sign-ins in Azure AD Identity Protection dashboard. |
| **Integration with Conditional Access** | Apply risk-based Conditional Access policies. |

---

## 🔁 Automated Risk-Based Policies

| Policy Type                | What it Does |
|----------------------------|--------------|
| **User risk policy**        | Requires password reset or blocks sign-in based on user risk. |
| **Sign-in risk policy**     | Requires MFA or blocks access if sign-in looks risky. |
| **MFA registration policy** | Ensures all users register for MFA up front. |

---

## 🛠️ Example Scenarios

| Scenario | Identity Protection Action |
|----------|-----------------------------|
| User's credentials found on dark web | Flag as high-risk user → Require password reset |
| Sign-in from an anonymous IP address | Flag sign-in risk → Require MFA |
| Sign-in from different country in short time | Impossible travel detected → Block access or challenge |

---

## 🔐 License Requirement

- Requires **Azure AD Premium P2**.

---

## 📝 Exam Tips

- **Azure AD Identity Protection** detects and responds to **identity risks**.
- It works with **User Risk**, **Sign-in Risk**, and **Risky Users/Sign-ins**.
- Can **automate responses** using Conditional Access policies.
- Requires **Azure AD Premium P2**.
- You may be asked:  
  👉 *Which feature uses machine learning to detect risky user behaviors and enforce automated responses?*  
  ✅ Answer: **Azure AD Identity Protection**

---