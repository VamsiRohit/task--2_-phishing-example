# task--2_-phishing-example
# 🛡️ Cyber Security Internship – Task 2

## 📧 Phishing Email Analysis Report

### 🔍 Task Overview
Analyze a suspicious email and identify phishing characteristics to understand how attackers use deception and social engineering.

---

## 📌 1. Email Summary

- **Subject**: High-severity alert: Phish delivered due to tenant or user override  
- **Sender Email**: microsoft@email-records.com  
- **Claimed Brand**: Microsoft / Office 365  
- **Date**: 01/22/2021  
- **Screenshot**: See attached image in the repo

---

## ⚠️ 2. Phishing Indicators

### ✅ 2.1 Fake Sender Email Address
- Real Microsoft emails come from `@microsoft.com`.
- This one comes from `@email-records.com`, which is **not a Microsoft-owned domain** → likely spoofed.

### ✅ 2.2 Urgent, Fear-Based Subject
- The subject creates panic: "High-severity alert".
- This is a classic **social engineering tactic** to rush the user into action.

### ✅ 2.3 Suspicious Link
- A call-to-action button: **"View alert details"**
- The link is hidden behind a button, which could easily redirect to a **malicious phishing site**.

### ✅ 2.4 Generic Content
- No recipient name or personalization.
- Uses vague terms like “sent by Unknown to” which further lowers credibility.

### ✅ 2.5 Branding Imitation
- Microsoft and Office 365 logos are used.
- Attackers often **copy official design** to appear legitimate, but logos alone don’t prove authenticity.

### ✅ 2.6 Technical Jargon as Distraction
- The message includes a technical-looking ID: `2aec-43aa-a943-...`, which has **no practical verification purpose**.
- This is meant to **confuse or convince** non-technical readers.

---

## ✅ 3. Conclusion

This email shows multiple signs of phishing:
- Spoofed sender
- Hidden malicious link
- Urgency-based deception
- Lack of personalization
- Faked brand visuals

📌 **It should be reported and deleted. Never click on links or enter credentials from such emails.**

---

## 📁 4. Files in This Repo

- `README.md` – This analysis
- `phishing_email_screenshot.jpeg` – The screenshot of the phishing email

---

## 🎯 Key Concepts Demonstrated

- Phishing detection
- Email spoofing awareness
- Social engineering
- Email header and content analysis


