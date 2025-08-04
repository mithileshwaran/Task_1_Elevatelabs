# 🚨 Cyber Security Internship - Task 1: Port Scanning & Network Reconnaissance

## 📁 Repository: Task_1_Elevatelabs  
## 👤 Intern Name: Mithileshwaran A
## 🗓️ Date: 04-August-2025

---

## 🎯 Objective

To scan the local network using **Nmap**, identify active devices and open ports, and understand the risks of exposed network services.  
This task helped build practical skills in reconnaissance — the first phase of ethical hacking.

---

## 🛠 Tools Used

- **Nmap** (via Zenmap GUI)
- **Operating System:** Windows 10
- **Target IP Range:** `192.168.104.0/24`

---

## 🔍 Command Used


```bash
nmap -sS 192.168.104.0/24

---

📂 Output File: scan_result.txt
🖼️ Screenshot File: nmap_result_gui.png
🖼️ Zenmap Scan Result

⚠️ Security Observations

    Port 22 (SSH) was open – could be brute-forced if weak credentials are used.

    Port 80 (HTTP) was detected – transmits unencrypted data.

    Port 445 (SMB) – may be vulnerable to exploits like EternalBlue.

📘 What I Learned

    🧠 I learned how to use Nmap for scanning a local network using both command line and GUI (Zenmap).

    🔍 Understood the concept of IP ranges, port numbers, and services that typically run on each port.

    🧪 Practiced using the TCP SYN scan, and learned how it checks for open ports in a stealthy way.

    🔐 Gained awareness of the security risks involved when services like SSH, HTTP, and SMB are exposed.

    📝 Learned how to write a README.md file in Markdown format, and organize files for GitHub submission.

📁 Files in This Repository

    scan_result.txt – Output of Nmap scan

    nmap_result_gui.png – Screenshot of Zenmap output

    README.md – This file

```bash
nmap -sS 192.168.104.0/24
