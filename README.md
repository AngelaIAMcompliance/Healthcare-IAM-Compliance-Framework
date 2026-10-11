# Enterprise Healthcare IAM Compliance Framework (Keycloak & Docker)

## 📌 Project Overview
Engineered a containerized, production-ready Identity and Access Management (IAM) infrastructure using Keycloak via Docker Desktop to securely manage user access pipelines across a simulated healthcare network (`Healthcare-Solutions`). 

This project bridges **CompTIA Security+ concepts (AAA, RBAC, Least Privilege)** with strict regulatory frameworks (**HIPAA Security Rule § 164.312 & NIST SP 800-53**) to demonstrate an audit-ready, hardened security baseline.

---

## 📑 Full Assessment & Evidence Report
The complete engineering architecture, configuration matrices, and visual proof of testing are documented in the formal report.

👉 **[Click Here to View the Full Technical Compliance Report (PDF)](<Healthcare-Solutions IAM Report.pdf>)**

---

## 🛡️ Core Regulatory Controls Demonstrated in Report
* **Granular Role-Based Access Control (RBAC):** Segmented user privileges across 5 clinical departments to enforce strict HIPAA Separation of Duties (SoD).
* **Identity Hardening & Credential Hygiene:** Deprecated default bootstrap account vulnerabilities and engineered a dedicated, named root administrator (`secopsadmin`).
* **Automated Brute-Force Intrusion Defenses:** Configured automated temporary account lockouts triggering instantly upon 3 failed login attempts.
* **Comprehensive Audit Trails:** Configured an immutable 90-day retention loop policy for User and Admin event tracking with full object representation data.
* **Lifecycle Flow Testing:** Verified real-world security policies by simulating the onboarding pipeline of a high-privileged identity, forcing a password reset, and intercepting non-compliant credentials in real-time.

---

## 🛠️ Technology Stack
* **Identity Engine:** Keycloak 26.8.0 (Containerized image)
* **Sandbox Containerization:** Docker Desktop for Mac (Isolated localhost virtualization)
* **Documentation Frameworks:** HIPAA Security Rule § 164.312 & NIST SP 800-53

