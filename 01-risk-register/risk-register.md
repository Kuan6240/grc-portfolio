# Cybersecurity Risk Register

## 1. Project Overview

**Project type:** Educational GRC simulation  
**Organization:** Northstar Community Services (fictional)  
**Assessment scope:** Employee accounts, company laptops, cloud email, and customer information  
**Assessment purpose:** Identify cybersecurity risks, prioritize remediation, and document recommended controls.

This project demonstrates foundational skills in cybersecurity risk identification, risk scoring, mitigation planning, and remediation tracking.

## 2. Risk Scoring Methodology

Likelihood and impact are each scored from 1 to 5.

**Likelihood**
- 1 — Rare
- 2 — Unlikely
- 3 — Possible
- 4 — Likely
- 5 — Almost certain

**Impact**
- 1 — Negligible
- 2 — Minor
- 3 — Moderate
- 4 — Major
- 5 — Severe

**Risk score = Likelihood × Impact**

| Score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

These thresholds are illustrative and would normally be approved by the organization's risk owners.

## 3. Risk Register

| ID | Risk scenario | Likelihood | Impact | Score | Rating | Recommended treatment |
|---|---|---:|---:|---:|---|---|
| R-01 | An employee account is compromised because multi-factor authentication (MFA) is not enforced. | 4 | 5 | 20 | Critical | Enforce MFA, prioritize privileged accounts, and monitor suspicious sign-ins. |
| R-02 | A phishing email tricks an employee into disclosing credentials. | 4 | 4 | 16 | High | Provide phishing awareness training, deploy email protections, and establish a reporting process. |
| R-03 | A lost or stolen laptop exposes sensitive information because disk encryption is not verified. | 3 | 5 | 15 | High | Enforce full-disk encryption and maintain device inventory and management. |
| R-04 | A former employee retains access because account deactivation is delayed. | 3 | 4 | 12 | High | Establish a documented offboarding checklist and promptly revoke access. |
| R-05 | Important files cannot be recovered after ransomware or accidental deletion. | 3 | 5 | 15 | High | Maintain protected backups and periodically test restoration. |
| R-06 | Sensitive customer information is accessible to staff who do not need it. | 3 | 4 | 12 | High | Apply least privilege, review access periodically, and remove unnecessary permissions. |

## 4. Remediation Tracking

| Risk ID | Priority action | Suggested owner | Target timeframe | Status |
|---|---|---|---|---|
| R-01 | Enforce MFA | IT Administrator | Within 30 days | Open |
| R-02 | Improve phishing defenses and training | Security Coordinator | Within 45 days | Open |
| R-03 | Verify laptop encryption | IT Administrator | Within 30 days | Open |
| R-04 | Document and test offboarding | HR and IT | Within 30 days | Open |
| R-05 | Test backup restoration | IT Administrator | Within 45 days | Open |
| R-06 | Review access permissions | System Owners | Within 60 days | Open |

*Owners and timeframes are proposed examples, not actual assignments or completed remediation.*

## 5. Framework Alignment

Potential reference points for further analysis include:

- **NIST Cybersecurity Framework 2.0:** Govern, Identify, Protect, Detect, Respond, and Recover.
- **NIST SP 800-53:** Relevant control families include Access Control, Identification and Authentication, Awareness and Training, and Contingency Planning.

Specific control mappings should be verified against the framework before being treated as formal compliance evidence.

## 6. Limitations

This is a fictional educational exercise. Risk ratings are illustrative and have not been validated through interviews, technical testing, or a real organizational assessment. No actual controls have been tested, and no risks have been formally accepted by a risk owner.

## 7. Skills Demonstrated

- Risk identification and documentation
- Likelihood and impact scoring
- Risk prioritization
- Mitigation recommendations
- Remediation tracking
- Introductory NIST framework awareness

