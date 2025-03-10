# ANZ Cybersecurity Simulation

## Repository Description  
This repository contains solutions and documentation for the **Cyber@ANZ Virtual Job Simulation**, which provides hands-on experience in cybersecurity investigations, focusing on **social engineering threats and digital forensics**.

## 📌 Quick Overview  
**Key Skills Gained:**  
- 🛡️ Social Engineering Investigation  
- 📧 Phishing Email Analysis  
- 🌐 Network Traffic Investigation  
- 🕵️‍♂️ Open Source Intelligence (OSINT)  
- 📝 Security Report Writing 

## 📂 Contents  

### 🔍 Task 1: Social Engineering Investigation  
- **Analyze emails** to identify phishing attempts, suspicious links, and malicious attachments.  
- **Report findings** to help determine whether emails should be blocked or released. 

### 🌐 Task 2: Digital Investigation  
- Examine a **packet capture (PCAP) file** to investigate potential cybersecurity threats using open-source tools.  

---

## 🔍 Task 1: Social Engineering Investigation  

### 📌 Task Overview  
You have been assigned **7 emails** to investigate. Some of these emails may contain **malicious content**, such as:  
- **Phishing attempts** targeting private account credentials  
- **Malicious attachments** that may contain malware  
- **Suspicious links** leading to fraudulent websites  

Your task is to **analyze each email** and determine whether it should be **blocked or released** based on its content and security risks.  

### 🎯 What You'll Learn  
- How to **identify phishing emails** and their warning signs  
- The impact of **malicious email content** in cybersecurity threats  
- How to properly **document and report findings** in an investigation  

### 🛠️ What You'll Do  
1. **Review the emails** provided in the PDF (`/resources/email_to_investigate.pdf`).  
2. **Analyze each email** for security threats, focusing on:  
   - **Sender authenticity** (email address verification)  
   - **Attachments** (malicious file indicators)  
   - **Embedded links** (safe vs. fraudulent URLs)  
   - **Content and language** (phishing red flags)  
3. **Use the provided answer template** (`/resources/email_analysis_template.docx`) to document:  
   - Whether the email is **safe or malicious**  
   - The **reasons** for classification (e.g., phishing attempt, suspicious attachment, domain mismatch)  
   - Suggested **actions** (block, release, or further review)  

### 🔒 Best Practices for Email Security  
- **Verify sender authenticity** before trusting any email.  
- **Hover over links** to check if they match the expected domain.  
- **Do not open attachments** from unknown or suspicious sources.  
- **Check for spelling errors, urgency, or threats**—common phishing tactics.  
- **Report suspicious emails** to IT/security teams rather than engaging with them.  

## 🌐 Task 2: Digital Investigation  

### 📌 Task Overview  
Suspicious network activity has been detected from a **user on the ANZ network**. A **laptop has been flagged** in the security systems due to **unusual internet traffic**, requiring an investigation to determine the files accessed and images viewed by the user.  

A **packet capture (PCAP) file** containing recent network activity has been provided. The objective is to analyze the network traffic, extract artifacts, and document findings in a structured report.  

### 🛠️ Investigation Process  

1️⃣ **Wireshark Installation**  
   - Wireshark is required to open and analyze the PCAP file.  
   - [Download Wireshark](https://www.wireshark.org/download.html) *(Free to use!)*  

2️⃣ **HxD (Hex Editor) Installation**  
   - A hex editor is needed for deeper packet analysis.  
   - [Download HxD](https://mh-nexus.de/en/hxd/)  

3️⃣ **PCAP File Analysis**  
   - The network activity file is located in the **resources folder**. (./resources/Digital_Investigation Task (pcap file).pcapng)  

4️⃣ **Network Traffic Examination**  
   - Use **Wireshark** to inspect packet details and filter relevant traffic.  
   - Use **HxD** to analyze packet contents at a binary level.  
   - Identify **accessed files, viewed images, and suspicious network requests**.  

5️⃣ **Findings Documentation**  
   - The provided **task template** must be used to report findings. (./resources/Task 2 - Answer Template) 

### 🔒 Best Practices for Network Forensics  
✅ Apply **Wireshark filters** to isolate specific traffic patterns  
✅ Identify **HTTP requests, FTP transfers, and DNS queries**  
✅ Examine **suspicious IP addresses and domain connections**  
✅ Extract **embedded files and images** from network packets  
✅ Maintain **detailed documentation of investigative steps**  

---

## 🚀 About This Project  
This project simulates **real-world cybersecurity tasks** at **ANZ Australia**, enhancing skills in:  
✅ Email threat analysis  
✅ Network forensics  
✅ Security documentation  

---
🔗 **Note:** This is a self-paced job simulation designed to develop cybersecurity investigation skills. 

