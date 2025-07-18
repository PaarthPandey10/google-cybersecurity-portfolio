# PASTA Threat Model – Sneaker Marketplace App Security Review

> Applying the PASTA (Process for Attack Simulation and Threat Analysis) framework to assess the threat landscape of a new mobile sneaker marketplace app.

---

## Overview

This project simulates a **threat modeling activity** using the PASTA framework to identify potential risks in a mobile application designed for sneaker collectors and enthusiasts. The app facilitates buying and selling of sneakers, handling sensitive user data and financial transactions. By going through all **seven stages of the PASTA model**, I performed a complete risk assessment to guide secure app development.

---

## Key Highlights

- **Business & Security Objectives**:
  - Enable secure sneaker transactions between users.
  - Protect user data and payment information.
  - Ensure compliance with data protection regulations like GDPR/CCPA.

- **Technical Scope**:
  - Prioritized technologies: `API`, `PKI`, `SHA-256`, `SQL`.
  - Focused on APIs due to their critical role in real-time data transfer, secure authentication, and backend integration. SQL was prioritized due to injection risks.

- **Threat Analysis**:
  - **External threats**: SQL injection, session hijacking, brute-force login.
  - **Internal threats**: Lack of prepared statements, insecure API logic, exposed test endpoints.

- **Vulnerability Analysis**:
  - Missing input validation and improper SQL query handling.
  - Weak session management and encryption practices.
  - Potential flaws in user permission handling or default admin accounts.

- **Attack Modeling**:
  - Attackers could:
    - Exploit SQL injection through unvalidated inputs.
    - Hijack sessions via stolen cookies or XSS.
    - Abuse exposed API endpoints lacking authentication.

- **Security Controls**:
  - Use **prepared SQL statements** and ORM to mitigate injection.
  - Enforce **MFA** and rate limiting for login attempts.
  - Secure sessions using HttpOnly cookies and automatic timeout.
  - Encrypt all communications with **TLS 1.3** and store hashes using **SHA-256**.

---

## Takeaway

This activity emphasizes the need for structured threat modeling using frameworks like PASTA to systematically **analyze threats and prioritize mitigations** before launch. For an app handling real-time payments and personal data, early security planning ensures a safer product and reduces future risks from data breaches or exploit attempts.

---

## Contact

For feedback or questions:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) • [GitHub](https://github.com/paarthpandey10) • paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
> Course: Google Cybersecurity Professional Certificate
