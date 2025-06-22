# DNS and ICMP Network Analysis

> An investigation into unreachable DNS service using network packet analysis.

---

## Overview

This document analyzes DNS and ICMP packet behavior during a website access failure. Using tcpdump, the activity explores how the system's DNS request resulted in ICMP “destination port unreachable” errors and helps identify which protocols were involved and impacted.

---

## Key Highlights

- Identified DNS and ICMP protocol involvement using tcpdump.
- Determined service interruption due to UDP packets being undeliverable to port 53.
- Investigated packet structure including timestamps, source/destination IPs, and flags.
- Demonstrated how ICMP responses expose service-level failures.

---

## Contact

For any questions or feedback, reach out:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) | [GitHub](https://github.com/paarthpandey10) | paarthdxb@gmail.com

—

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
> Course: Google Cybersecurity Professional Certificate
