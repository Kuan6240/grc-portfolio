# Security Control Assessment Matrix

## 1. Project Overview

**Organization:** Northstar Community Services (fictional)  
**Project type:** Educational GRC simulation  
**Framework reference:** NIST SP 800-53 Rev. 5  
**Purpose:** Document selected security controls, identify evidence that could demonstrate implementation, and record illustrative assessment results.

This project demonstrates introductory skills in security control assessment, evidence collection planning, gap identification, and remediation tracking.

## 2. Assessment Matrix

| Control Area | Security Objective | Example Evidence to Review | Assessment Procedure | Illustrative Status |
|---|---|---|---|---|
| Access Control | Restrict access to authorized users | User access list, access policy, approval records | Compare user permissions with approved job responsibilities | Needs validation |
| Identification and Authentication | Require appropriate authentication, including MFA where applicable | Identity provider configuration, MFA policy, authentication settings | Review settings and verify enforcement for selected accounts | Needs validation |
| Awareness and Training | Educate employees about security risks | Training policy, completion records, awareness materials | Check whether training requirements and completion records are documented | Needs validation |
| Audit and Accountability | Record relevant security events | Logging configuration, sample audit logs, retention settings | Review logging coverage and confirm logs are retained according to policy | Needs validation |
| Configuration Management | Maintain approved and secure system configurations | Configuration standards, asset inventory, change records | Compare a sample of systems against documented configuration requirements | Needs validation |
| Contingency Planning | Prepare to recover systems and data | Backup policy, backup logs, recovery test results | Review backup coverage and evidence of restoration testing | Needs validation |

## 3. Evidence Quality Checklist

For each item of evidence, an assessor should consider:

- **Relevance:** Does the evidence relate to the control being assessed?
- **Currency:** Is it recent enough for the assessment?
- **Authenticity:** Can its source be verified?
- **Coverage:** Does it cover the required systems, users, or processes?
- **Sufficiency:** Is there enough evidence to support the conclusion?

Evidence should be collected and handled in accordance with organizational policies and access permissions.

## 4. Illustrative Findings Log

| Finding ID | Observation | Potential Risk | Recommended Next Step | Status |
|---|---|---|---|---|
| F-01 | MFA enforcement has not yet been verified | Accounts may be vulnerable to credential compromise | Review identity settings and test enforcement with authorization | Open |
| F-02 | Backup restoration evidence has not yet been reviewed | Recovery capability is unconfirmed | Review recent restoration test records | Open |
| F-03 | Periodic access review records have not yet been examined | Excessive access may go undetected | Obtain review records and confirm approval and follow-up | Open |

These are assessment questions and hypothetical observations, not confirmed control failures.

## 5. Assessment Status Definitions

- **Implemented:** Sufficient evidence supports that the control is implemented within the assessed scope.
- **Partially implemented:** Evidence supports some, but not all, required implementation.
- **Not implemented:** Assessment evidence supports that the required control is absent or not implemented.
- **Needs validation:** Evidence has not yet been collected or reviewed sufficiently to reach a conclusion.
- **Not applicable:** The control does not apply to the documented scope, with justification.

## 6. Framework Reference

NIST SP 800-53 Rev. 5 provides a catalog of security and privacy controls. Relevant control families for this exercise include:

- AC — Access Control
- IA — Identification and Authentication
- AT — Awareness and Training
- AU — Audit and Accountability
- CM — Configuration Management
- CP — Contingency Planning

Family names are provided as introductory references. Formal assessments should select applicable controls and verify their exact requirements against the authoritative NIST publication and the organization's approved control baseline.

## 7. Limitations

This is a fictional educational exercise. No actual systems were examined, no real evidence was collected, and no formal control assessment or audit was performed.

## 8. Skills Demonstrated

- Security control assessment planning
- Evidence identification and review
- Preliminary gap analysis
- Findings documentation
- Remediation recommendations
- Introductory NIST SP 800-53 familiarity
