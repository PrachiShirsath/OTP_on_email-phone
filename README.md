# 🔐 OTP Sender (Email + SMS) using Python  

## 📌 Project Overview  
This project is a Python-based OTP (One-Time Password) authentication system that sends secure verification codes via **Email 📧** and **Mobile 📱**. It simulates real-world authentication systems used in login verification, account registration, and password recovery.

---

## 🚀 Key Features  

### 🔹 🔢 OTP Generation  
- Generates random OTP (4–8 digits)  
- Ensures secure and unique codes  

---

### 🔹 📧 Email Integration  
- Sends OTP using Gmail SMTP  
- Uses App Password for secure login  

---

### 🔹 📱 SMS Integration  
- Sends OTP using Twilio API  
- Supports real mobile verification  

---

### 🔹 ✅ Input Validation  
- Validates email format  
- Prevents incorrect input  

---

### 🔹 🔐 OTP Verification  
- User enters OTP  
- System verifies correctness  
- Displays success or failure  

---

### 🔹 ☁️ Google Colab Support  
- Fully runnable on Google Colab  
- No local setup required  

---

## 🧠 Technologies Used  

- 🐍 Python  
- 📧 smtplib (Email Sending)  
- ✅ email-validator  
- 📱 Twilio API  

---

## ⚙️ How It Works  

1. 👤 User enters email and mobile number  
2. 🔢 System generates OTP  
3. 📤 OTP is sent via:  
   - 📧 Email (SMTP)  
   - 📱 SMS (Twilio)  
4. ⌨️ User enters received OTP  
5. 🔐 System verifies OTP  

---

## Sample output

Enter Email: user@gmail.com  
Enter Mobile: +919876543210  
Generated OTP: 483920  

✅ OTP sent to Email  
✅ OTP sent to Mobile  

Enter OTP: 483920  
✅ Verified Successfully  

---
