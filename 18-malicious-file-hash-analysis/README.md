# Malicious File Hash Analysis

> Investigated a suspicious file documented its indicators of compromise (IoCs) through the Pyramid of Pain model.

---

## Overview

This project simulates the initial steps in malware investigation by applying **threat intelligence analysis** techniques. The activity focused on examining a suspicious file hash, and categorizing associated IoCs using the **Pyramid of Pain** framework to assess detection difficulty and attacker disruption.

---

## Key Highlights

- **Tool Used**:`SHA256 hashing`

- **Objective**: 
  - Determine the malicious nature of an email attachment.
  - Identify and classify IoCs from VirusTotal based on the Pyramid of Pain.

- **Pyramid of Pain Levels Analyzed**:
  - **Hash Values** – Used to detect the exact malicious file.
  - **IP Addresses / Domain Names** – Indicators found through VirusTotal’s threat intel.
  - **File Names / Strings** – Helped correlate with known malware samples.

- **Scenario**:
  - An employee received a phishing email with a password-protected spreadsheet.
  - Upon opening the file, malicious code executed.
  - As a SOC analyst, I extracted the file, hashed it, and used VirusTotal to uncover linked IoCs.

---

## Takeaway

The activity emphasized how **early-stage malware analysis** and public threat intelligence platforms like VirusTotal aid in identifying known threats and **disrupting attacker operations** by targeting high-level IoCs.

---

## Contact

**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) • [GitHub](https://github.com/paarthpandey10) • paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)
> 
> Course: Google Cybersecurity Professional Certificate
