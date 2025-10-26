# 🔍 Task 3 – PC Vulnerability Scan
**Cyber Security Internship**

---

## 🎯 Goal
To perform a vulnerability assessment on my personal computer using **Nessus Essentials**, uncover potential security weaknesses, and understand mitigation strategies.

---

## 🛠 Tools & Environment
- **Scanner:** Nessus Essentials (Free Version)  
- **Target:** Localhost (`127.0.0.1`)  
- **Scan Policy:** Basic Network Scan  

---

## ⏱ Scan Timeline
| Start Time | End Time | Duration | Vulnerabilities Found | CVSS Version |
|------------|----------|----------|---------------------|--------------|
| 10:29 AM   | 10:45 AM | 17 min   | 24                  | 3.0          |

---

## ⚠️ Critical Findings

### 1️⃣ Outdated Software
- **Severity:** Critical (CVSS 9.0)  
- **Risk:** Exposes known exploits  
- **Mitigation:** Update all software via Windows Update  

### 2️⃣ SMB Signing Not Required
- **Severity:** High (CVSS 8.1)  
- **Risk:** Vulnerable to man-in-the-middle attacks  
- **Mitigation:** Enable SMB signing in Windows Local Security Policy  

### 3️⃣ Open RDP Port (3389)
- **Severity:** High (CVSS 8.4)  
- **Risk:** Brute-force attacks possible  
- **Mitigation:** Disable RDP or restrict access via firewall rules  

---

## 📸 Evidence
- `1_summary.png`  
- `2_vulnerabilities.png`  


---

## 🧠 Takeaways
- Mastered the workflow for a basic vulnerability scan  
- Learned CVSS scoring and prioritization  
- Hands-on experience with Nessus Essentials  
- Identified real-world PC-level security risks and solutions  

---

