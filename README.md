# Web Vulnerability Assessment

## Overview
This project demonstrates a vulnerability assessment conducted against the Metasploitable 2 virtual machine using Nmap.

## Tools Used
- Nmap
- Kali Linux
- Canva

## Objectives
- Identify open ports
- Detect vulnerable services
- Classify security risks
- Recommend remediation steps

## Key Findings
| Vulnerability | Risk |
|---|---|
| vsftpd 2.3.4 | High |
| UnrealIRCd Backdoor | Critical |
| Telnet Enabled | High |

## Deliverables
- Professional Vulnerability Assessment Report
- Scan Evidence
- Findings Documentation

## Skills Demonstrated
- Vulnerability Analysis
- Risk Assessment
- Security Reporting
- Network Enumeration

# Phishing Email Detection & Awareness System

## Overview
This project demonstrates phishing email analysis using sample emails, header review, browser tools, and risk classification.

## Objectives
- Identify phishing indicators
- Classify emails as Safe, Suspicious, or Phishing
- Explain phishing risks in simple business language
- Provide prevention and awareness guidelines

## Tools Used
- Email Header Analyzer
- Browser Tools
- Google Docs / MS Word / PDF
- Canva

## Key Skills
- Phishing detection
- Email threat analysis
- Risk communication
- Security awareness reporting

## Deliverables
- Phishing Detection & Awareness Report
- Email sample analysis
- Prevention guidelines


# API Security Risk Analysis

## Overview
This project demonstrates an API Security Risk Analysis conducted against the JSONPlaceholder public test API using Postman and Browser DevTools.

The objective of the assessment was to identify common API security risks related to authentication, authorization, data exposure, request handling, and rate limiting.

---

## Target API
JSONPlaceholder Test API

https://jsonplaceholder.typicode.com

---

## Tools Used
- Postman
- Browser DevTools
- Google Chrome
- JSONPlaceholder API
- Canva / PDF Documentation

---

## Skills Demonstrated
- API Security Analysis
- Authentication & Authorization Review
- Risk Identification
- Security Documentation
- API Request Testing
- Business-Focused Risk Communication

---

## Key Security Risks Identified

| Finding | Risk Level |
|---|---|
| Public API Access Without Authentication | Medium |
| Excessive Data Exposure | Medium |
| Weak Authorization / ID-Based Access | Medium |
| POST Requests Accepted Without Authentication | Medium |
| Missing Visible Rate Limiting | Low–Medium |

---

## Methodology
The following steps were performed during the assessment:

1. API endpoint enumeration
2. Request and response inspection
3. Authentication testing
4. Authorization review
5. Data exposure analysis
6. Rate-limiting observation
7. Risk classification and reporting

---

## API Endpoints Tested

```http
GET /users
GET /users/1
GET /posts
POST /posts
GET /comments
```

---

## Sample POST Request

```json
{
  "title": "Security Test",
  "body": "Testing API input validation",
  "userId": 1
}
```

---

## Deliverables
- API Security Risk Analysis Report (PDF)
- Postman Testing Screenshots
- Findings Documentation
- Security Recommendations

---

## Repository Structure

```text
task-3-api-security-risk-analysis/
│
├── README.md
├── report/
├── screenshots/
├── findings/
└── methodology/
```

---

## Key Learning Outcomes
This project helped build practical understanding of:
- API authentication risks
- Access control weaknesses
- Excessive data exposure
- Secure API design principles
- API security assessment workflows

---

## References
- https://jsonplaceholder.typicode.com
- https://owasp.org/www-project-api-security/
- https://www.postman.com

---

## Disclaimer
This assessment was conducted only against publicly available demo APIs intended for testing and educational purposes. No unauthorized or harmful activity was performed.
