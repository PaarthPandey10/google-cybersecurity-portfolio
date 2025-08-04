# IP Allow List Automation

> Python algorithm to manage and update access permissions based on IP addresses.

---

## Overview

This project presents a simple yet effective Python script for automating the management of restricted content access through an IP allow list. The script reads a list of approved IP addresses from `allow_list.txt`, cross-references it with a predefined removal list, and updates the file by removing entries that no longer require access. The algorithm streamlines access control procedures within your organization while minimizing the chance of human error.

---

## Key Highlights

- Reads and parses IPs from an existing allow list file.
- Converts file content into a list structure for efficient manipulation.
- Iterates through a removal list and eliminates matching IPs from the allow list.
- Rewrites the updated list back to the original file using Python's file-handling methods.
- Uses core methods like `.read()`, `.split()`, `.remove()`, and `.join()` for clean and readable logic.

---

## Contact

For any questions or feedback, reach out:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) | [GitHub](https://github.com/paarthpandey10) | paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
>  
> Google Cybersecurity Professional Certificate
