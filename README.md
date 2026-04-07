# Performing-Social-Engineering-Attack
# 🛡️ Social Engineering Attack Simulation using SET (Credential Harvesting Lab)

## 📌 Overview

This project demonstrates a practical implementation of a Social Engineering attack using the Social Engineer Toolkit (SET). The lab focuses on phishing techniques, website cloning, and credential harvesting to understand how attackers exploit human behavior rather than system vulnerabilities.

---

## 🎯 Objectives

* Understand the concept of Social Engineering attacks
* Perform a phishing attack using SET toolkit
* Clone a legitimate website
* Capture user credentials through a fake login page
* Analyze the risks and real-world implications of such attacks

---

## 🧠 Concepts Covered

* Social Engineering
* Phishing Attacks
* Credential Harvesting
* Website Cloning
* Human Psychology Exploitation
* Attack Lifecycle (Recon → Exploit → Capture)

---

## 🛠 Tools & Technologies Used

* Parrot OS / Kali Linux
* Social Engineer Toolkit (SET)
* Web Browser (Firefox/Chrome)
* Email Service (Gmail)

---

## ⚙️ Lab Setup

* Virtual Machine environment (Parrot OS as attacker machine)
* Local IP used for hosting cloned website
* Victim simulation using browser/email

---

## 🧪 Step-by-Step Procedure

### 1. Launch SET Toolkit

* Open terminal
* Run: `setoolkit`
* Select:

  * Social Engineering Attacks
  * Website Attack Vectors
  * Credential Harvester Attack Method

---

### 2. Clone Target Website

* Choose Site Cloner option
* Enter attacker machine IP address
* Provide target website URL
* Tool creates a replica of the website

---

### 3. Craft Phishing Email

* Open email client (Gmail)
* Create a fake but attractive message
* Embed malicious link pointing to attacker machine
* Use URL masking to make link look legitimate

---

### 4. Victim Interaction

* Victim clicks phishing link
* Fake website opens (looks identical to real site)
* Victim enters username and password

---

### 5. Credential Capture

* Captured credentials are displayed in terminal
* Data is stored in plain text
* Attacker successfully obtains sensitive information

---

## 📊 Results

* Successfully cloned a legitimate website
* Executed phishing attack
* Captured user credentials in real-time
* Demonstrated how easily users can be deceived

---

## ⚠️ Key Learnings

* Human behavior is the weakest link in cybersecurity
* Phishing attacks rely more on psychology than technical exploitation
* Fake websites can closely mimic real ones
* User awareness is critical to prevent attacks

---

## 🔐 Security Recommendations

* Always verify URLs before entering credentials
* Avoid clicking unknown or suspicious links
* Use HTTPS and check security indicators
* Enable multi-factor authentication (MFA)
* Conduct regular security awareness training

---

## 📸 Screenshots

(Add your screenshots here)

* SET Toolkit Interface
* Website Cloning Process
* Phishing Email Example
* Fake Login Page
* Captured Credentials Output

---

## 🚀 Future Improvements

* Implement detection mechanisms for phishing
* Analyze phishing emails using tools like Netcraft & PhishTank
* Extend lab to real-time phishing detection

---

## ⚠ Disclaimer

This project was conducted in a controlled lab environment for educational purposes only. Unauthorized use of these techniques is strictly prohibited.

---

## 💼 Author

(Your Name)

Cybersecurity Enthusiast | Ethical Hacking Learner | CEH Candidate
