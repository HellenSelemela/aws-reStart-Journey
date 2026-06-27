# Introduction to Amazon Linux AMI & Terminal Essentials

## 📌 Project Overview
This project demonstrates foundational expertise in remote cloud infrastructure access and Linux system administration. Through this lab, I established secure remote terminal sessions to an Amazon Elastic Compute Cloud (EC2) instance and navigated the native Linux standard help system to audit core system utilities.

---

## 🛠️ AWS Services & Linux Technologies Used
* **Amazon EC2 (Elastic Compute Cloud):** Managed a cloud-based host deployed within a public subnet of a custom Amazon Virtual Private Cloud (VPC).
* **Secure Shell (SSH):** Configured and initialized encrypted remote management sessions using PuTTY and private key (`.ppk`) authentication.
* **Linux Shell Environments:** Utilized the Amazon Linux 2023 terminal interface for system verification and command execution.
* **Linux Manual System (man):** Navigated standard documentation structures to parse system headers, syntax rules, and utility arguments.

---

## 🚀 Lab Workflow & Core Competencies

### Task 1: Secure Remote Infrastructure Access
* **Credential Management:** Handled cloud authentication mechanisms by leveraging a standalone private key file (`labuser.ppk`) paired with the instance's public IPv4 address.
* **SSH Session Initiation:** Established a stateful terminal connection over port 22 through PuTTY, successfully authenticating as the administrative `ec2-user`.

### Task 2: Linux System Documentation & Component Auditing
* **Interface Navigation:** Executed runtime utilities like `man man` to interface with the core kernel and application documentation environment directly from the command line.
* **Structural Parsing:** Analysed standard formatting sections including **NAME**, **SYNOPSIS**, **DESCRIPTION**, and **OPTIONS** to interpret how command-line utilities manipulate systems resources.
