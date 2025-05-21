# 🧪 owasp-juice-shop-pen-testing

A project demonstrating penetration testing techniques on the **OWASP Juice Shop** application, including enumeration, brute-force attacks, and exploitation of vulnerabilities, with detailed reports and findings. 🛡️

---

## 🔍 OWASP Juice Shop Penetration Testing Project

This repository contains the work for a penetration testing project on the OWASP Juice Shop application. The project demonstrates the process of identifying vulnerabilities, exploiting them, and documenting findings. 🧷📝

---

## 📚 Project Overview

This project was created as part of a **cybersecurity learning program**. It focuses on understanding common web vulnerabilities and how attackers exploit them using penetration testing tools and techniques. 💻🛠️

---

## 📦 What’s Included

1. 🗂️ **Reports**  
   A detailed report of all the testing performed, including methodologies, vulnerabilities found, and recommendations.

2. 🎥 **Video Demonstration**  
   A video walkthrough of the attacks conducted on the Juice Shop.

3. 📜 **Scripts and Logs**  
   - Commands and scripts used during testing  
   - Output logs from tools like Dirb and Burp Suite

4. 🖼️ **Screenshots**  
   Proof of findings, including discovered admin paths and successful exploits

---

## 🧰 Tools Used

- 🔎 **Dirb**: For URL enumeration and directory brute-forcing  
- 🧪 **Burp Suite**: To perform brute-force attacks and analyze requests  
- 🕸️ **OWASP ZAP**: For scanning and finding vulnerabilities  
- 🐱‍💻 **Kali Linux**: The primary environment for all tests

---

## 🚨 Key Findings

- 🔐 **Admin URL Enumeration**: Discovered hidden admin page through Dirb and accessed it using credentials found via brute-force  
- 💣 **Brute Force Attack**: Successfully cracked the admin password using Burp Suite  
- 🕵️‍♂️ **Sensitive Data Disclosure**: Identified user reviews leaking admin information

---

## 🧭 How to Use This Repository

1. 📁 Navigate to the `reports/` folder for detailed documentation  
2. 🎞️ Check the `video/` folder for the video demonstration  
3. 💻 Explore the `scripts/` folder for commands and tools used  
4. 📸 Refer to the `screenshots/` folder for evidence of findings

---

## ✅ Recommendations

- 🔒 Secure admin pages with strong passwords and multi-factor authentication  
- 🚫 Limit login attempts to prevent brute-force attacks  
- 🧼 Avoid exposing sensitive data in user-facing sections

---

🔧 Built for educational purposes in ethical hacking and cybersecurity training.  
⚠️ Use responsibly and always with proper authorization!
