# 🔍 Task 3: Basic Vulnerability Scan using Nessus Essentials

## 🎯 Objective
To perform a **basic vulnerability scan** on my personal computer using **Nessus Essentials** and identify potential system vulnerabilities based on their severity and CVSS scores.

---

## 🧰 Tools and Setup
- **Tool Used:** Nessus Essentials (Free Version)
- **Developer:** Tenable, Inc.
- **Operating System:** Windows 10 (you can change if using Linux/macOS)
- **Target:** Localhost (`127.0.0.1`)
- **Scan Type:** Basic Network Scan

---

## ⚙️ Steps Performed

### **1️⃣ Download and Register**
- Visited [Tenable Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
- Registered with my email to get a **free activation code**
- Downloaded and installed the appropriate version for my system

### **2️⃣ Installation**
- Ran the installer and completed the setup
- Opened browser and navigated to `https://localhost:8834`
- Selected **“Nessus Essentials”** and entered the activation code
- Created local credentials (username & password)
- Waited for Nessus to **download and compile plugins** 

### **3️⃣ Creating a New Scan**
- Clicked **New Scan → Basic Network Scan**
- Entered:
  - **Name:** Localhost Vulnerability Scan  
  - **Description:** Scanning my local system for vulnerabilities  
  - **Target:** `127.0.0.1`
- Clicked **Save**

### **4️⃣ Running the Scan**
- Navigated to **My Scans** and launched the saved scan
- Waited for the scan to complete 

### **5️⃣ Reviewing Results**
- Opened the completed scan report
- Observed total vulnerabilities categorized by severity:
  - Critical
  - High
  - Medium
  - Low
  - Info
- Checked CVSS scores and descriptions for each vulnerability

### **6️⃣ Exporting the Report**
- Clicked **Export → PDF → Custom → Include Summary + Details**
- Saved the report as `Nessus_Report.pdf`

### **7️⃣ Documentation**
- Took screenshots of:
  - Dashboard with completed scan
  - Vulnerability summary chart
  - Example of one high/critical vulnerability details

---

## 🩺 Key Learnings
- Understood how **vulnerability scanning** identifies security weaknesses.
- Learned about **CVSS (Common Vulnerability Scoring System)**.
- Gained experience in assessing **risk levels and mitigations**.
- Improved awareness of system configuration security.

---
  
### ✅ Outcome
Successfully performed a **basic vulnerability assessment** using Nessus Essentials and gained hands-on experience with real-world cybersecurity scanning tools.
