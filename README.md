# 🔐 Log Analysis & Threat Detection (SSH Logs)

## 📌 Overview
This project demonstrates basic log analysis and threat detection using SSH authentication logs in a Kali Linux environment. The objective was to identify suspicious login activity and understand how security analysts detect potential brute-force attempts.

---

## 🧪 Scenario
A simulated brute-force attack was performed by attempting multiple failed SSH logins using an invalid user account.

---

## ⚙️ Tools Used
- Kali Linux  
- SSH Service  
- journalctl (log analysis)

---

## 🚀 What I Did
- Started SSH service in a local environment  
- Simulated failed login attempts using an invalid user  
- Analyzed system logs using `journalctl`  
- Filtered failed login attempts  
- Counted total failed attempts  
- Extracted source IP address  

---

## 🧠 Key Findings
- Multiple failed login attempts were detected in SSH logs  
- All attempts originated from the same IP (::1 – localhost)  
- A total of 3 failed attempts were observed  
- Indicates simulated brute-force behavior  

---

## 🧠 Key Learnings
- How authentication logs can be analyzed for suspicious activity  
- Basics of brute-force attack detection  
- Importance of monitoring login attempts in security operations  
- Introduction to SOC-level log analysis  

---

## ⚠️ Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.
