# icmp-dos-attack-analysis-nist-csf
Analysis of an ICMP Flood DoS attack using the NIST Cybersecurity Framework, including detection, response, and mitigation strategies.
# 🚨 ICMP Flood DoS Attack Analysis (NIST CSF)

## 📌 Overview
This project analyzes a Denial of Service (DoS) attack caused by an ICMP flood targeting a company's internal network. The analysis follows the NIST Cybersecurity Framework (CSF) to identify vulnerabilities, assess impact, and recommend mitigation strategies.

---

## ⚠️ Incident Summary
- **Attack Type:** ICMP Flood DoS  
- **Cause:** Misconfigured firewall (no ICMP filtering or rate limiting)  
- **Impact:** Network outage for ~2 hours, internal services unavailable  

---

## 🧠 NIST CSF Breakdown

### 🔍 Identify
- Firewall misconfiguration allowed unrestricted ICMP traffic  
- Lack of monitoring increased exposure  

### 🛡 Protect
- Firewall hardening (default-deny rules)  
- ICMP rate limiting  
- Network segmentation  

### 👀 Detect
- IDS/IPS implementation  
- SIEM-based monitoring  
- Traffic anomaly detection  

### 🚨 Respond
- Block malicious ICMP traffic  
- Isolate affected systems  
- Analyze logs and attack patterns  

### 🔄 Recover
- Restore critical services first  
- Validate system integrity  
- Resume normal operations  

---

## 🛠 Skills Demonstrated
- Network Security Analysis  
- Incident Response (NIST CSF)  
- Threat Detection  
- Security Documentation  

---

## 📎 Project Files
- Incident Report (PDF)

---

## 💡 Key Takeaways
- Misconfigured firewalls create major vulnerabilities  
- Monitoring is essential for early detection  
- Defense-in-depth reduces attack impact  
