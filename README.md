# Phishing Analysis Lab Submission 

<p align="center">
  <img src="https://img.shields.io/badge/Lab-Day%2021-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Topic-Phishing%20Analysis-critical?style=for-the-badge&logo=datadog" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=checkmarx" />
  <img src="https://img.shields.io/badge/Phishing-Email%20Threats-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IOC-Indicator%20of%20Compromise-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Incident%20Response-Workflow-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tool-VirusTotal-blue?style=for-the-badge&logo=virustotal" />

</p>


## Task
Investigate the reputation of a suspicious domain from a phishing email.

## Domain Analyzed
`secure-paypai.com`

## Tools Used
- VirusTotal (https://www.virustotal.com)

## Summary
- The domain was flagged as **malicious** by 1 out of 94 security vendors on VirusTotal.  
- Details are documented in `investigation.md`, and a supporting screenshot is attached. 


## Files Included
- investigation.md
- domain-reputation.png

## ✍️ Observations and Learnings

### 📌 Observations
- The phishing email used a **lookalike domain** (`secure-paypai.com`) to impersonate PayPal.
- **Email header analysis** revealed inconsistencies:
  - Poor SPF/DKIM validation.
  - Mismatch between "From" name and email domain.
- Only **1/94** vendors flagged it initially — shows **new phishing domains bypass detection**.
- Urgency and fear tactics were used in the message tone.
- URLs were hidden behind **deceptive display text**.

---

### 📚 Learnings
- **Domain Reputation Checking** is crucial, even if AV engines don't immediately flag it.
- **Email Header Analysis** can expose true sender origin.
- **VirusTotal and Open-Source Tools** are critical in investigations.
- **Visual inspection** of emails (hovering over links) often reveals phishing attempts.
- **Phishing techniques are evolving**, using typosquatting and deception tactics.
- **User Awareness and Training** remains critical.

---


## Submitted By

<p align="center">
  <img src="https://img.shields.io/badge/Name-Obakeng%20Shuma---Blue?style=for-the-badge&logo=github" />
</p>


---

## 🏷️ Tags
`#Phishing` `#EmailSecurity` `#ThreatAnalysis` `#IncidentResponse` `#VirusTotal` `#IOC` `#CyberSecurity`
