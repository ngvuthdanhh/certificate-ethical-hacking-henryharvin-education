# Blue Team Defense Labs – Ethical Hacking

These labs focus on defensive techniques against common attacks.

---

## 1. Network Monitoring & Intrusion Detection
- Tools: Wireshark, Suricata, Snort  
- Objective: Detect abnormal traffic (port scans, ARP poisoning).  
- Exercise: Configure IDS to alert on Nmap SYN scan.

---

## 2. Malware Analysis (Basic)
- Tools: Cuckoo Sandbox, VirusTotal  
- Objective: Analyze unknown executable safely.  
- Exercise: Upload sample → observe file, registry, and network activity.  

---

## 3. Password Policy Enforcement
- Tools: Windows GPO / Linux PAM  
- Objective: Enforce complexity, expiration, and lockout rules.  
- Exercise: Configure password policies and test brute-force prevention.

---

## 4. Web Application Firewall (WAF) Setup
- Tools: ModSecurity, Nginx WAF module  
- Objective: Block SQL Injection & XSS payloads.  
- Exercise: Deploy WAF → attempt test payloads → verify logs.

---

## 5. Incident Response Simulation
- Scenario: Company email compromised via phishing.  
- Steps:
  1. Containment (disable compromised account)  
  2. Eradication (scan endpoints, block IOC domains)  
  3. Recovery (reset passwords, restore clean backup)  
  4. Lessons learned (awareness training, email filtering)
