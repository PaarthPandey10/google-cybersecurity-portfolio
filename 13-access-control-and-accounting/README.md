# Identify and Improve Access Controls in a Small Business Scenario

> Investigating a post-employment access control failure and recommending key authentication and authorization improvements to reduce security risks.

---

## Overview

This project explores a real-world-inspired access control failure where a former contractor’s admin account was still active years after contract expiration. The incident highlights how misconfigured user permissions and a lack of account lifecycle management can expose critical business systems. Based on the analysis, I recommended key access control improvements including timely account deactivation, role-based access, and implementation of multi-factor authentication (MFA).

---

## Key Highlights

- Analyzed event logs from 10/03/23 involving a Legal/Administrator user account with IP: `152.207.255.255`.
- Detected access to payroll systems by a **former contractor**, Robert Taylor Jr., whose contract ended in **2019**.
- Identified lack of account expiration and insufficient role-based access controls.
- Recommended security improvements:
  - Automatically **expire inactive or contractor accounts** after a defined period (e.g., 30 days).
  - **Limit access privileges** for non-employees and contractors.
  - **Enable MFA** across all sensitive systems and accounts.
  - Enforce **strong password and audit policies** to detect unauthorized access.

---

## Takeaway

This activity demonstrates the dangers of poor account lifecycle management and over-permissive access in small businesses. Implementing clear boundaries around user access—especially for contractors and former employees—reduces the risk of internal threats and unauthorized activity. Controls like account expiration policies and MFA should be foundational in any cybersecurity strategy.

---

## Contact

For questions or feedback, reach out:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) • [GitHub](https://github.com/paarthpandey10) • paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
> Course: Google Cybersecurity Professional Certificate
