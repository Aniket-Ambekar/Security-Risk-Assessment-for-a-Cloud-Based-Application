# Security Risk Assessment for a Cloud-Based Application

## Objective
The goal of this project is to assess security risks in a cloud-based application by identifying assets, threats, vulnerabilities, and recommending risk-based security controls.

---

## Architecture Overview
The application consists of:
- End users accessing a web application
- A cloud-hosted application layer
- A backend database storing sensitive data
- Identity and Access Management (IAM) controlling access
- Centralized logging and monitoring

---

## Asset Identification
Key assets identified include:
- User credentials and identity data
- Application and business data
- Cloud infrastructure resources
- Logs and audit records

---

## Threat Identification
Threats were identified using a structured approach:

- Credential compromise
- Unauthorized access due to weak IAM controls
- Data exposure from misconfigured resources
- Lack of auditability and monitoring
- Privilege escalation through excessive permissions

---

## Vulnerability Analysis
Identified vulnerabilities include:
- Absence of multi-factor authentication
- Overly permissive IAM roles
- Insufficient logging and alerting
- Limited network segmentation

---

## Risk Evaluation
| Risk | Impact | Likelihood |
|----|----|----|
| Credential compromise | High | Medium |
| Unauthorized access | High | Medium |
| Data exposure | High | Low |
| Privilege misuse | Medium | Medium |

---

## Recommended Security Controls
- Enforce least-privilege IAM policies
- Enable MFA for sensitive and privileged access
- Centralize logging and enable monitoring
- Apply network segmentation to reduce blast radius

---

## Residual Risk
While recommended controls reduce overall risk, continuous monitoring and periodic reassessment are required as threats evolve.
