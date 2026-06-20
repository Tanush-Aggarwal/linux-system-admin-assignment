# 🐧 Linux System Administration – Assignment Submission

> **Course:** Operating Systems / Linux Administration  
> **Total Marks:** 20 Points (5 Questions × 4 Marks Each)  
> **Topic:** Linux File Systems, Permissions, I/O Operations & Storage Management

---

## 📋 Assignment Overview

This repository contains all reports, observations, and documentation for the Linux System Administration assignment. Each question has been addressed with appropriate Linux commands and detailed findings.

---

## 📁 Repository Structure

```
linux-assignment/
│
├── README.md                          ← This file
│
├── Q1_Linux_Environment_Verification/
│   └── Environment_Report.txt         ← Linux environment & user account details
│
├── Q2_Secure_Project_Workspace_Setup/
│   └── Project_Workspace_Report.txt   ← Directory structure & permissions report
│
├── Q3_File_System_and_Link_Analysis/
│   └── Link_Analysis_Report.txt       ← Hard link vs symbolic link analysis
│
├── Q4_File_Access_and_IO_Investigation/
│   └── IO_Investigation_Report.txt    ← File access & I/O operations report
│
└── Q5_Storage_Health_Assessment/
    └── Storage_Assessment_Report.txt  ← Storage health & disk usage report
```

---

## 📝 Questions Summary

| # | Question | Topic | Marks | Report File |
|---|----------|-------|-------|-------------|
| 1 | Linux Environment Verification | User accounts, shell, network | 4 | `Environment_Report.txt` |
| 2 | Secure Project Workspace Setup | File permissions, ownership, umask | 4 | `Project_Workspace_Report.txt` |
| 3 | File System and Link Analysis | Inodes, hard links, symbolic links | 4 | `Link_Analysis_Report.txt` |
| 4 | File Access and I/O Investigation | File descriptors, I/O redirection | 4 | `IO_Investigation_Report.txt` |
| 5 | Storage Health Assessment | Disk usage, mounted filesystems | 4 | `Storage_Assessment_Report.txt` |

---

## 🔧 Tools & Commands Used

- `whoami`, `id`, `groups` – User identity verification
- `echo $SHELL`, `pwd`, `ls -la` – Shell and directory inspection
- `ping`, `ifconfig` / `ip addr` – Network connectivity
- `mkdir`, `chmod`, `chown`, `umask` – Permissions and ownership
- `ln`, `ln -s`, `ls -li` – Hard and symbolic links
- `lsof`, `ulimit`, `fdisk`, `df`, `du` – I/O and storage analysis
- `vi` editor – Report creation and editing

---

## 📌 Notes

- All reports were created/edited using the **vi editor** as required.
- Screenshots of command outputs are referenced within each report.
- Commands were executed on a **Linux/Ubuntu** environment.

---

*Submitted as part of the Linux System Administration coursework.*
