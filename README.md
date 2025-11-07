
# 🧑‍💻 Cybersecurity Practical Assignments & Projects

## 📂 Project Overview

This repository contains practical assignments and mini-projects completed as part of the BCA Cyber Security curriculum.
It includes two key submissions:

1. Semester 3: Linux Practical Assignments
2. Semester 5:Data Recovery using TestDisk (Digital Forensics Project)

🔐 Project 1 – Data Recovery using TestDisk (Semester 5)
 🧾 Problem Statement

A user accidentally deleted critical files from their workstation. The task is to **recover the deleted files** while **maintaining data integrity** and **preventing damage** to existing data.

🎯 Objectives

1. Identify the appropriate data recovery tools and techniques for the specific file system.
2. Recover the deleted files securely without overwriting existing data.
3. Verify the integrity of recovered files using hashing (MD5, SHA1, SHA256).
4. Educate the user on preventive measures and backup strategies

⚙️ Tools & Technologies Used

Operating System:** Ubuntu/Linux
Tool:TestDisk (Open-Source Data Recovery Utility)
Hashing Utilities:`md5sum`, `sha1sum`, `sha256sum`
Other Linux Commands:`fdisk`, `ls`, `stat`, `cat`, `rm`

🧠 Implementation Summary

 Used `sudo fdisk -l` to identify all partitions.
 Launched  TestDisk to scan for deleted files.
Recovered files and validated their integrity via SHA-256 hashing.
Ensured that recovery was performed without modifying original data.

📈 Findings

✅ Deleted files were successfully recovered.
✅ Integrity verified using cryptographic hashes.
✅ No corruption or overwrite occurred.

🔮 Future Scope

* Automation of recovery using scripts.
* Integration with forensic tools (Autopsy, Sleuth Kit).
* Use of AI for reconstructing partially overwritten data.
* Blockchain-based integrity tracking for evidence handling.


🧰 Project 2 – Linux Practical Assignments (Semester 3)

A collection of foundational Linux operations used in cybersecurity and system administration.

 📘 Chapters Covered

1. File Management
2. Permissions
3. Process Management
4. System Information
5. Package Management
6. User and Group Management
7. Networking
8. Text Processing & Searching
9. Archiving & Compression
10. Deploying a LAMP Server (Linux, Apache, MySQL, PHP)

### ⚡ Example Topics & Commands

| Topic                  | Commands                                    | Description                             |
| ---------------------- | ------------------------------------------- | --------------------------------------- |
| **File Management**    | `mkdir`, `cp`, `mv`, `cat`                  | Create, copy, and rename files.         |
| **Permissions**        | `chmod`, `adduser`, `su`                    | Manage file access control.             |
| **Process Management** | `ps aux`, `kill <pid>`                      | Monitor and terminate processes.        |
| **System Info**        | `lscpu`, `df -h`, `free -h`                 | Display CPU, memory, and disk details.  |
| **Networking**         | `ifconfig`, `ping`, `whois`                 | Check connectivity and network details. |
| **Text Processing**    | `grep`, `sed`, `awk`, `find`                | Search, filter, and manipulate text.    |
| **Archiving**          | `tar -czvf`, `tar -xzvf`                    | Compress and extract directories.       |
| **LAMP Deployment**    | `sudo apt install apache2 mysql-server php` | Setup and configure web server stack.   |


 🧩 Additional Project (Forensics Case Study)

 Problem Statement:

Investigate a cyber incident and acquire evidence from a suspect’s computer while ensuring data integrity.

Objectives:

1. Acquire a forensically sound disk image**.
2. Maintain chain of custody and data integrity.
3. Prepare data for forensic analysis.


 Learning Outcomes

* Practical understanding of Linux-based system operations.
* Real-world exposure to data recovery and digital evidence handling.
* Application of forensic tools in controlled environments.
* Enhanced awareness of cybersecurity best practices.

## 🧾 References

* [TestDisk Official Documentation](https://www.cgsecurity.org/wiki/TestDisk)
* Linux Manual Pages (`man`, `--help`)
* Bharatiya Sakshya Adhiniyam 2023 — Digital Evidence Reference



 👨‍💻 Author

Ganesh Balaji Bharkade
BCA (Cyber Security Specialization)
Tilak Maharashtra Vidyapeeth, Pune
📞 Contact: +91 9970271965
📧 Email:ganeshbharkade1122@gmail.c
 om
 Linkdin: in/ganesh-bharkade-1742b72aa
 

