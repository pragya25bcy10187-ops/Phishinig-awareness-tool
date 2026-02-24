# Phishinig-awareness-tool
Web-based phishing detection tool that analyzes suspicious messages and links using rule-based risk scoring to improve cybersecurity awareness.
# 🔐 Phishing Awareness & Detection Analyzer

## 📖 Introduction
Phishing Awareness & Detection Analyzer is a web-based cybersecurity tool designed to help users identify suspicious messages and malicious links. The system analyzes user input and calculates a phishing risk score using rule-based detection techniques.

This project was developed as a hackathon / academic mini-project to promote cybersecurity awareness and safe browsing habits.

---

## 🚨 Problem Statement
Phishing attacks are one of the most common cybersecurity threats today. Attackers send fake emails, SMS messages, and links that appear legitimate but aim to steal sensitive information such as passwords, OTPs, and banking details.

Many users fall victim due to:
- Lack of awareness
- Emotional manipulation (urgent messages)
- Fake rewards and offers
- Shortened malicious URLs

---

## 🎯 Project Objective
The objective of this project is to:

- Detect suspicious phishing indicators in text
- Identify insecure (http) links
- Detect shortened URLs
- Calculate a risk score
- Classify results as Safe, Suspicious, or High Risk
- Improve cybersecurity awareness

---

## ⚙️ System Architecture

User Input  
↓  
Keyword & Link Scanner  
↓  
Risk Score Calculation  
↓  
Result Display  

---

## 🧠 How It Works

1. The user pastes a message or link into the analyzer.
2. The system converts input into lowercase for uniform checking.
3. It scans for:
   - Suspicious keywords (urgent, verify, OTP, free, win)
   - Insecure links (http)
   - Short URLs (bit.ly, tinyurl, goo.gl)
4. Risk score increases based on detection.
5. The final result is displayed:

   - ✅ Safe (No phishing indicators)
   - ⚠ Suspicious (Few warning signs)
   - 🚨 High Risk (Multiple phishing indicators)

---

## 🛠 Technologies Used

- HTML (Structure)
- CSS (Styling & UI Design)
- JavaScript (Logic & Risk Analysis)
- Visual Studio Code (Development Environment)

---

## ✨ Features

- Message Analyzer
- Risk Score Detection
- Cyber-themed UI
- Full-screen responsive layout
- Back navigation functionality
- Beginner-friendly interface

---

## 🚀 Future Enhancements

- AI-based phishing detection
- Machine learning integration
- Real-time URL verification API
- Database storage for analyzed messages
- User authentication system
- Dark/light mode toggle


---

## 💻 Installation & Usage

1. Download or clone the repository
2. Open the project folder
3. Open index.html in browser
4. Paste message and analyze



---

⭐ Securing the Digital Future
