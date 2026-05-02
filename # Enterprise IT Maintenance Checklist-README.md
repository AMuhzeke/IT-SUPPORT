# Enterprise IT Maintenance Checklist

A comprehensive, frequency-based maintenance framework for Windows Systems Administrators and Infrastructure Engineers. This repository contains a structured approach to managing Active Directory, Server Hardware, and Core Network Services.

## 📋 Overview

Maintaining a high-availability environment requires more than reactive troubleshooting; it requires disciplined, scheduled audits. This checklist categorizes essential IT tasks into logical intervals to ensure that nothing from DNS replication to physical hardware warranties is overlooked.

## 🗂️ Structure of the Checklist

The `Maintenance-Checklist.xlsx` file is organized into the following tabs:

| Schedule | Focus Areas |
| :--- | :--- |
| **Daily** | High-impact services: AD Replication, critical logs, and backup success checks. |
| **Weekly** | System performance monitoring and security log reviews. |
| **Monthly** | Directory hygiene: Cleaning up inactive accounts, DNS record auditing, and software patching. |
| **Quarterly** | Governance: Group Policy (GPO) audits and permission reviews. |
| **Bi-Annually** | Physical Layer: Server BIOS/Firmware updates, RAID controller health, and Generator testing. |
| **Annually** | Lifecycle Management: Warranty tracking for business-critical equipment and long-term capacity planning. |

## 🛠️ Key Categories

### 🔹 Active Directory
Covers the health of the domain, including replication integrity (Replmon/Logs), DNS zone maintenance, and OU structure authorization.

### 🔹 Hardware & Storage
Detailed checks for SAN firmware, RAID battery status, and physical environmentals (Generators and UPS).

### 🔹 Severity Logging
Includes a dedicated sheet for **Logging Severity Levels** to help technicians standardize how they report findings (e.g., distinguishing between a routine notification and a critical failure).

## 🚀 How to Use This

1.  **Fork this Repository:** Customize the tasks to fit your specific infrastructure needs.
2.  **Assign Ownership:** Use the frequency sheets to delegate tasks to specific team members.
3.  **Track Progress:** It is recommended to add a "Status" or "Date Completed" column to the sheets for audit trails.
4.  **Automate:** Use the checklist as a requirement doc for setting up automated monitoring (e.g., Nagios, Zabbix, or PowerShell scripts).

## 🤝 Contributing

If you have suggestions for new maintenance tasks (especially for Cloud or Hybrid environments), feel free to open a PR or an issue.

---
*Maintained for IT Professionals and System Administrators.*
