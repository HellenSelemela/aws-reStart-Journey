# AWS EC2 Resizing and Infrastructure Scaling Lab

## 📌 Project Overview
This project demonstrates practical expertise in cloud infrastructure management, specifically focusing on the vertical scaling of compute resources, storage optimization, and termination protection safeguards within **Amazon Web Services (AWS)**. 

Through this lab, I successfully managed the lifecycle of an EC2 instance, modified security firewall rules, optimized elastic block storage (EBS), and monitored system reboots through the live serial console.

---

## 🛠️ AWS Services & Technologies Used
* **Amazon EC2 (Elastic Compute Cloud):** Provisioned and vertically scaled a cloud-based Linux web server.
* **Amazon EBS (Elastic Block Store):** Dynamically resized and updated volume capacities (`gp3`).
* **VPC Security Groups:** Configured inbound firewall rules to control web traffic protocols.
* **EC2 Serial Console / Instance Boot Monitoring:** Verified system initialization state during server resizing.

---

## 🚀 Lab Walkthrough & Tasks Implemented

### Task 1 & 2: Infrastructure Initialization & Assessment
* Launched and inspected the pre-provisioned baseline EC2 `Web Server` instance.
* Verified configuration parameters including Public/Private IPv4 spaces and baseline instance tier (`t3.micro`).

### Task 3: Inbound Firewall & Security Group Configuration
* Navigated to network security settings to audit open ports and modified attached Security Group rules to safely permit inbound HTTP traffic on port 80.

### Task 4: Vertical Scaling (Compute & Elastic Block Storage)
To accommodate increased resource demand, the server environment was scaled seamlessly:
1.  **Compute Upgrade:** Gracefully stopped the instance and changed the instance type from `t3.micro` (1 vCPU, 1 GiB RAM) to **`t3.small`** (2 vCPU, 2 GiB RAM).
2.  **Storage Expansion:** Modified the root EBS volume directly, expanding the storage threshold capacity from **8 GiB to 10 GiB** utilizing the optimized `gp3` volume state.
3.  **Boot Verification:** Monitored the console output to verify that the upgraded kernel and expanded space initialized flawlessly.

*💾 Amazon Linux System Boot Output:*
![Amazon Linux Boot Screen](aws-linux-boot.png)

---

## 🔑 Key Takeaways & Cloud Competencies
* **Vertical Scaling Proficiency:** Safely scaling virtual machine capacities up based on organizational load changes.
* **Live System Monitoring:** Monitoring cloud console initialization logs to ensure system health post-maintenance windows.
