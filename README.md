<div align="center">

# QAZEEM SAMSUDEEN TEMITOPE
### **Junior Cybersecurity Analyst | SOC Analyst Tier 1 |penetration testing| Cloud Security & Identity Governance**
**Defending Enterprise Infrastructure • Active Directory Hardening • SIEM Detection Engineering**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:qazeemsamshudeen@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/2348130406501)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://www.credly.com/users/qazeem-samsudeen)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/blaqqsec)

---

</div>

## 🛡️ About Me

I am an investigative, results-driven **Cybersecurity Analyst & SOC Tier 1 Practitioner** with hands-on experience spanning Security Operations (SOC), Active Directory administration, cloud identity security (AWS IAM), and vulnerability assessment.

Holding a **B.Sc. in Criminology and Security Studies** from the **University of Ilorin (UNILORIN)**, I combine investigative methodologies with deep technical tradecraft—ingesting multi-source telemetry into Splunk SIEM, hunting credential-based attacks (MITRE ATT&CK T1110), implementing Least Privilege (PoLP) on Windows Server architectures, and simulating cloud privilege escalation scenarios.

- 🔭 **Current Focus:** SOC Tier 1 Monitoring, Active Directory Pentesting, SIEM Detection Engineering, and Cloud Security.
- 💼 **Experience:** Cybersecurity Intern at **Bincom Dev Center** | Information Security Intern at **UNILORIN Cybersecurity Unit**.
- 📜 **Certifications:** Cisco IT Support Specialist, Cisco Networking Basics, Cisco Intro to Cybersecurity, Splunk Core Fundamentals.
- 🎯 **Career Goal:** Safeguarding enterprise infrastructure and critical assets as a SOC Analyst / Cloud Security Analyst.

---

## 🚀 Featured Security Projects

### 1. Enterprise Active Directory Architecture & Least-Privilege Hardening
`WINDOWS SERVER 2022` `ACTIVE DIRECTORY` `AGDLP MODEL` `GROUP POLICY` `PoLP`

An enterprise directory service deployment on Windows Server 2022 (`BlaqqSec-lab.local`) focused on establishing role-based access control, helpdesk delegation, and audit logging without granting excessive administrative privileges.

- **Hierarchical OU Architecture:** Structured organizational units separating administrative tiers, staff workstations, and service accounts.
- **AGDLP Role-Based Access Control:** Implemented Account → Global Group → Domain Local Group → Permission hierarchy to prevent privilege creep.
- **Helpdesk Rights Delegation:** Delegated password reset and account unlock privileges to Tier-1 Helpdesk without Domain Admin escalation.
- **GPO Security Hardening:** Enforced domain-wide USB storage device blocking and configured Advanced Security Audit Policies (Event IDs 4624, 4625, 4688).

---

### 2. Splunk SIEM Threat Monitoring & T1110 Incident Attribution
`SIEM` `SPLUNK ENTERPRISE` `SPL HUNTING` `MITRE ATT&CK T1110` `INCIDENT RESPONSE`

Ingested multi-source telemetry from Linux auth logs and Windows event logs into Splunk Enterprise to detect and attribute multi-threaded brute-force attacks in real time.

- **Log Ingestion & Parsing:** Configured Splunk forwarders and indexes to capture authentication attempts, SSH sessions, and failed logon bursts.
- **Custom SPL Threat Hunting:** Authored targeted SPL queries calculating authentication velocity, threshold anomalies, and failed logon sequences (Event ID 4625).
- **Incident Attribution:** Attributed 100% of brute-force bursts to adversary IP addresses and automated containment triggers via Fail2ban.
- **SOC Executive Dashboard:** Designed dark-mode real-time visual dashboards tracking top attacked users, geographical origins, and timeline spikes.

---

### 3. Cloud Security: AWS IAM Privilege Escalation & Least-Privilege Remediation
`AWS CLOUD` `IAM` `PRIVILEGE ESCALATION` `CLOUDGOAT` `LEAST PRIVILEGE`

Simulated the industry-standard Rhino Security Labs **CloudGoat `iam__privesc_by_attachment`** attack lifecycle inside an isolated AWS cloud sandbox engine and engineered production-grade remediation guardrails.

- **Vulnerability Reproduction:** Provisioned low-privilege user `intern-qazeem` with an overly permissive `iam:AttachUserPolicy` wildcard permission (`Resource: *`).
- **Exploit Execution:** Abused attachment rights to bind `AdministratorAccess` (`*:*`) to the unprivileged identity, achieving root-level account takeover.
- **Least-Privilege Remediation:** Contained the compromise, revoked admin rights, and authored a hardened policy with strict read-only access.
- **Explicit Deny Guardrails:** Engineered an `ExplicitDeny` policy on all `iam:Attach*` and `iam:Put*` actions, permanently neutralizing escalation vectors.

---

### 4. Web Application Security & ModSecurity WAF Defense
`APACHE WAF` `MODSECURITY` `OWASP CRS` `VIRTUAL PATCHING` `WEB DEFENSE`

Deployed an enterprise reverse-proxy Web Application Firewall (WAF) using Apache and the OWASP Core Rule Set (CRS) to protect web applications against OWASP Top 10 exploits.

- **Rule Deployment:** Deployed 800+ OWASP CRS detection rules to intercept and inspect HTTP request payloads.
- **Virtual Patching:** Authored custom regular-expression rules to virtually patch known SQL Injection (SQLi) and Cross-Site Scripting (XSS) attack vectors with HTTP 403 Forbidden.
- **Evasion Testing:** Simulated obfuscated payloads to validate WAF inspection sensitivity and false-positive rates.

---

## 🛠️ Technical Skills & Security Toolkit

### Security Operations & Threat Monitoring
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-3949AB?style=for-the-badge&logo=virustotal&logoColor=white)
![urlscan.io](https://img.shields.io/badge/urlscan.io-008080?style=for-the-badge)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

### Identity & Access Governance (IAM)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D7?style=for-the-badge&logo=windows&logoColor=white)
![Group Policy](https://img.shields.io/badge/Group_Policy_(GPO)-005A9E?style=for-the-badge)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Least Privilege](https://img.shields.io/badge/Least_Privilege_(PoLP)-107C41?style=for-the-badge)
![RBAC / AGDLP](https://img.shields.io/badge/RBAC_/_AGDLP-5C2D91?style=for-the-badge)

### Vulnerability Assessment & Penetration Testing
![Nmap](https://img.shields.io/badge/Nmap-000000?style=for-the-badge)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)
![OpenVAS](https://img.shields.io/badge/OpenVAS-408000?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-136CB2?style=for-the-badge&logo=metasploit&logoColor=white)
![Nikto](https://img.shields.io/badge/Nikto-4B0082?style=for-the-badge)

### Operating Systems & Virtualization
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server_2022-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)

---

## 📜 Verified Certifications & Badges

| Certification / Badge | Issuing Organization | Verification Link |
| :--- | :--- | :--- |
| **IT Support Specialist** | Cisco Networking Academy | [Verify on Credly ↗](https://www.credly.com/badges/c54f5738-0c67-4e7c-8ca7-98c3bde4d51e) |
| **Networking Basics** | Cisco Networking Academy | [Verify on Credly ↗](https://www.credly.com/badges/38c54253-3e3f-43de-8eed-39aca261336d) |
| **Introduction to Cybersecurity** | Cisco Networking Academy | [Verify on Credly ↗](https://www.credly.com/badges/fd0065d5-d52e-450c-bd75-819c54f1ed65) |
| **Splunk Core Fundamentals / Certified Beginner** | Splunk Inc. | Verified Certificate |
| **Black-Box Penetration Testing** | NetworkWalks Academy | Verified Participation Certificate |
| **ByteMe CTF Certified Competitor** | ByteMe Cyber Defense | Certified Competitor (2026) |

**bytemecert**
![bytemecert](byteme-cert.png)

**cisco-IT customer-cert**
![cisco-IT-customer](cisco-IT-ustomer-support.PNG)

**cisco-cybersecurity-beginner**
![cisco-cybersecurity](cisco-cybersecurity-beginner.png)

**networking-basics**
![networking-basics-cert](networking-basics.png)

**networkwalks**
![networkwalk-certificate](networkwalk-certificate.png)

**splunk-cert**
![splunk-cert](splunk-beginner-certification.PNG)

 
---

## 🎓 Education & Background

- **B.Sc. in Criminology and Security Studies**  
  *University of Ilorin (UNILORIN), Ilorin, Nigeria* | **2022 – 2026**  
  *Focus:* Cyber Criminology, Organizational Risk Management, Security Intelligence, Compliance Governance (NDPA/NDPR/HIPAA).

---

<div align="center">

### 🤝 Let's Connect
**Open to Junior Cybersecurity Analyst, SOC Analyst Tier 1, and IT Security Opportunities.**

[LinkedIn](https://linkedin.com) • [Email](mailto:qazeemsamshudeen@gmail.com) • [WhatsApp](https://wa.me/2348130406501)

</div>
