# Phishing Investigation Report

## 1. Incident Summary

- Applied for a LinkedIn job by sending a resume via email.  
- Received a reply instructing submission of personal details via:  
  1. Website: `hxxp://navafiz[.]com`  
  2. WhatsApp contact  

**Observation:** Classic **recruitment phishing tactic**.

---

## 2. Email Analysis

### Red Flags

- Instant "application reviewed" response  
- Unprofessional email formatting  
- Sender domain: `example@fake-recruitment-mail.com`  
- Request for personal details over WhatsApp  
- No HR name, signature, or company verification  

### Email Indicators (`indicators/email_metadata.txt`)


---

## 3. URL & Domain Analysis

### VirusTotal Summary

| Engine / Source       | Result      |
|----------------------|------------|
| Bfore.Ai PreCrime     | Suspicious |
| Abusix                | Clean      |
| AlienVault            | Clean      |
| Phishtank             | Clean      |
| URLhaus               | Clean      |
| Others (Unrated)      | Unrated    |

### URLScan.io Summary

- **Domain:** navafiz.com  
- **IP Contacted:** 192.250.235.158 (Singapore)  
- **Hosting Provider:** WHG-SGP WHG Hosting Services Ltd  
- **HTTP Transactions Observed:** 3  
- **TLS Certificate:** R12, issued Oct 6, 2025, valid 3 months  
- **Verdict:** No classification  

---

## 4. Indicators of Compromise (IOCs)

### Malicious URL (`indicators/malicious_url.txt`)

### Email Indicators (`indicators/email_metadata.txt`)


---

## 5. Conclusion

- Confirmed phishing attempt targeting job seekers.  
- Tactics: fake website, WhatsApp request, urgent messaging.  
- Risk: collection of PII (personal information, CV, contact details).  
- Tools like VirusTotal, URLScan.io, and MXToolbox validate phishing threats.  

---

## 6. Recommendations

- Never submit personal info to unverified websites.  
- Avoid sharing personal details over WhatsApp with unknown recruiters.  
- Validate company domains via LinkedIn or WHOIS lookup.  
- Always check suspicious URLs using OSINT and cybersecurity tools.
