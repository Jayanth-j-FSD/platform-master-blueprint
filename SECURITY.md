## Unitreal Security Policy

Unitreal is a unified platform for identity, social, marketplace, collaboration, and payments. Security is a top priority throughout our development and operations. This document describes supported versions and how to report vulnerabilities, as well as the security principles we follow.

---

## 🔒 Supported Versions

We actively maintain and provide security updates for:

* **Unitreal 3.x** – Active (latest major version)
* **Unitreal 2.x** – Maintenance mode (critical fixes only)
* **Unitreal 1.x and below** – ❌ End-of-life (no security updates)

All users are encouraged to upgrade to a supported version immediately.

---

## 🛡️ Reporting a Vulnerability

To report a vulnerability, contact our security team:

📧 **Email:** [security@Unitreal.com](mailto:security@Unitreal.com)
🔐 **PGP Fingerprint:** `ABCD 1234 5678 9ABC DEF0 1234 5678 9ABC DEF0 1234`

Please include:

* Component and version affected
* Steps to reproduce the issue
* Proof-of-concept if available
* Any logs or relevant output

⚠️ If your report contains sensitive data, encrypt it using our PGP key.

We will:

* Acknowledge your report within 1 business day
* Provide an initial analysis within ~7 days
* Aim to patch critical issues within 90 days or sooner

Public disclosure will be coordinated with you after the patch is ready. Credit will be given unless anonymity is requested.

---

## 🔐 Security Principles We Follow

Unitreal’s architecture and policies are based on strong, modern security practices:

* **Zero Trust Model** – Every action is verified (identity, device, session)
* **Least Privilege Access** – No excess permissions granted
* **End-to-End Encryption** – TLS 1.3 for all traffic, strong crypto at rest
* **Audit Logging** – Immutable logs of all sensitive operations
* **Secure Defaults** – No insecure configs, strict CSP/security headers
* **Dependency Scanning** – Automated CVE tracking & patching
* **Regular Testing** – Code reviews, SAST, pentests, fuzzing
* **Incident Response Plan** – For rapid mitigation and root-cause tracing
* **Compliance Ready** – Aligned with GDPR, ISO 27001, PCI DSS

---

## 🤝 We Appreciate Responsible Disclosure

We welcome security research and will collaborate professionally. Thank you for helping protect the Unitreal ecosystem.
