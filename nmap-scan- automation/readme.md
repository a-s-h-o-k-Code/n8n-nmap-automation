# 🔐 n8n Cybersecurity Automation - Nmap Scan & Email Alert

This project is a simple cybersecurity automation workflow built using **n8n**.

It automatically:
- Runs an Nmap scan on a target host
- Collects scan output
- Sends the result to email using SMTP (Gmail)

## ⚙️ Workflow Steps
1. Trigger (Manual or Cron)
2. Execute Command (Nmap scan)
3. Email Send (SMTP)

## 🧰 Tools Used
- n8n (self-hosted)
- Nmap
- Gmail SMTP

## 📩 Output
The scan result is sent to the configured email address automatically.

## 🚀 How to Use
Import the JSON workflow into n8n
Install Nmap on your system
Configure SMTP credentials
Run the workflow

## 📌 Example Command
```bash

nmap scanme.nmap.org
