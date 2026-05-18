# 🛡️ FUTURE_CS_02 — Phishing Email Detection & Awareness Report

> **Future Interns | Cyber Security Internship 2026 | Task 2**
> 📅 Internship Period: 27 April 2026 – 27 May 2026
> 👤 Intern: **Steven Anthony** | 🏷️ Track: **CS** | Repo: **FUTURE_CS_02**

---

## 📋 Task Overview

**Task 2 — Phishing Email Detection & Awareness System**

| Field | Details |
|-------|---------|
| **Domain** | Cyber Security — Email Threat Analysis |
| **Target** | Real suspicious email from personal Gmail spam folder |
| **Scope** | Header analysis, domain investigation, URL scanning — read-only |
| **Tools** | MXToolbox · VirusTotal · Gmail Header Analyzer · Browser DevTools |
| **Deliverable** | Professional Phishing Detection & Awareness Report (PDF) |

---

## 📧 Email Analyzed

| Field | Details |
|-------|---------|
| **Subject** | Validated UPI and SEBI Check Tool |
| **Sender** | services@cdslindia.co.in |
| **Date** | 2 May 2026 |
| **Gmail Action** | Auto-placed in Spam folder |
| **Verdict** | 🟠 SUSPICIOUS |

---

## 🔍 Key Findings

| Finding | Detail | Risk |
|---------|--------|------|
| Gmail auto-spam detection | Email placed in spam folder automatically | 🔴 High |
| Generic sender display name | Shown only as "services" | 🟠 Medium |
| 71-minute delivery delay | 4,292 second delay at bulk mail relay | 🟠 Medium |
| Bulk mail infrastructure | Routed via broadside.co / bmail12.com | 🟠 Medium |
| SPF Multiple Records | DNS misconfiguration — more than one SPF record | 🟠 Medium |
| Dual DKIM keys | Two DKIM selectors found for domain | 🟡 Low |
| SPF/DKIM/DMARC Auth | All authentication checks pass | ✅ Low |
| URL Safety (VirusTotal) | 0/95 vendors flagged — leads to official SEBI portal | ✅ Safe |

---

## 🛠️ Tools Used

| Tool | Purpose | Evidence |
|------|---------|---------|
| **Gmail Show Original** | Raw header extraction | Screenshots in report |
| **MXToolbox Header Analyzer** | SPF/DKIM/DMARC validation, relay analysis | Screenshots in report |
| **MXToolbox SuperTool** | Domain MX record and DMARC policy lookup | Screenshots in report |
| **VirusTotal** | URL threat scanning (95 vendors) | Screenshots in report |
| **Chrome DevTools** | Safe link inspection | Used during analysis |

---

## 📁 Repository Structure

```
FUTURE_CS_02/
├── README.md
├── Phishing_Detection_Report_Steven_Anthony.pdf
└── screenshots/
    ├── 01_gmail_spam_folder.png
    ├── 02_email_header_original.png
    ├── 03_mxtoolbox_auth_pass.png
    ├── 04_mxtoolbox_relay_delay.png
    ├── 05_mxtoolbox_spf_issue.png
    ├── 06_mxtoolbox_dkim_keys.png
    ├── 07_mxtoolbox_headers_found.png
    ├── 08_virustotal_result.png
    └── 09_mx_domain_lookup.png
```

---

## 📄 Report

👉 [`Phishing_Detection_Report_Steven_Anthony.pdf`](./Phishing_Detection_Report_Steven_Anthony.pdf)

**Report Includes:**
- ✅ Introduction to phishing threats
- ✅ Tools used with methodology
- ✅ Full email header analysis (SPF/DKIM/DMARC/relay)
- ✅ URL scanning results (VirusTotal — 95 vendors)
- ✅ Risk classification with verdict table
- ✅ 10 common phishing indicators reference guide
- ✅ Prevention tips — Do's and Don'ts
- ✅ Classic phishing email example with annotated red flags
- ✅ Ethical statement

---

## 🏷️ Repository Descriptions (choose one)

1. `Task 2 - Phishing Email Detection & Awareness Report | Future Interns Cyber Security Internship 2026 | MXToolbox, VirusTotal, Header Analysis`
2. `Phishing email header forensics and awareness documentation | Future Interns CS Internship | FUTURE_CS_02`
3. `Cyber Security Task 2 - Real spam email analysis using MXToolbox and VirusTotal | Professional awareness report | Future Interns 2026`

---

## ⚠️ Ethical Statement

All analysis was conducted for **educational and awareness purposes only** using a real spam email received in a personal inbox. No systems were attacked, no unauthorized access was attempted, and no malicious links were clicked. All URLs were analyzed safely using VirusTotal's passive scanning service.

---

## 💡 Skills Gained

- Email header forensics and interpretation
- SPF, DKIM, DMARC authentication analysis
- Email routing and relay investigation
- URL threat scanning with VirusTotal
- Risk classification and security reporting
- Phishing awareness documentation

---

## 🔗 Connect

- 🏢 **Future Interns LinkedIn:** [linkedin.com/company/future-interns](https://www.linkedin.com/company/future-interns/)
- 💬 **Telegram:** [t.me/+SG6y8VRVN_sxNzQ1](https://t.me/+SG6y8VRVN_sxNzQ1)
- 🏷️ **Hashtags:** #futureinterns #cybersecurity #phishing #emailsecurity #ethicalhacking

---

*Prepared by Steven Anthony | Future Interns Cyber Security Internship 2026 | FUTURE_CS_02*
