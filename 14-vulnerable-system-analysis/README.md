# Vulnerability Assessment of a Publicly Accessible Database Server

> Identifying and mitigating critical risks posed by an exposed remote MySQL database used by a global e-commerce workforce.

---

## Overview

This project simulates a vulnerability assessment for a small e-commerce company that unknowingly left its remote database server open to the public for three years. As a cybersecurity analyst, I conducted a full risk analysis guided by **NIST SP 800-30 Rev. 1**, identified key threat vectors, and proposed a robust remediation strategy to protect sensitive business data and ensure operational continuity.

---

## Key Highlights

- **System Description**:
  - Linux-based server with 128 GB RAM hosting a **MySQL** database.
  - Publicly accessible over the internet with only basic SSL/TLS protections.
  - Used by globally distributed employees to retrieve customer intelligence.

- **Major Risks Identified**:
  - **High risk of unauthorized access** or data exfiltration due to open port exposure.
  - **Insider misuse** due to lack of fine-grained access control.
  - **Botnet and scanner attacks** targeting the public-facing endpoint.

- **Remediation Strategy**:
  - Implement **IP allow-listing** and remove open internet access.
  - Enforce **multi-factor authentication (MFA)** and **role-based access controls (RBAC)**.
  - Upgrade to **TLS 1.3** and deprecate outdated SSL configurations.
  - Introduce **firewall rules**, **network segmentation**, and **database auditing**.
  - Schedule **regular vulnerability scans** and patch cycles.

---

## Takeaway

This assessment emphasizes the importance of **minimizing attack surface** by securing externally facing systems. Even a single publicly exposed database can lead to massive reputational, legal, and financial damage. Proper access restrictions, encryption, and proactive monitoring are essential defenses in today’s threat landscape—especially for distributed or remote-first organizations.

---

## Contact

For questions or collaboration, feel free to connect:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) • [GitHub](https://github.com/paarthpandey10) • paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
> Course: Google Cybersecurity Professional Certificate
