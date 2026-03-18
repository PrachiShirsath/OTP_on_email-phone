# OTP_on_email-phone
🔐 OTP Sender (Email + SMS) using Python

This project is a simple Python-based application that generates a One-Time Password (OTP) and sends it to a user via Email and Mobile Number. It is designed as part of a lab activity to demonstrate real-world authentication mechanisms.

📌 Features

🔢 Generates random OTP (4 to 8 digits)

📧 Sends OTP to email using SMTP

📱 Sends OTP to mobile using Twilio API

✅ Validates email format

🔐 OTP verification system included

☁️ Works on Google Colab

🛠️ Technologies Used

Python

smtplib (for email sending)

email-validator

Twilio API (for SMS)

🚀 How It Works

User enters email and mobile number

System generates a random OTP

OTP is sent:

to email via SMTP

to mobile via SMS API

User enters received OTP

System verifies the OTP

⚙️ Setup Instructions
1. Install Dependencies
pip install email-validator twilio
2. Configure Email

Enable 2-Step Verification in Gmail

Generate App Password

Replace in code:

sender_email = "your_email@gmail.com"
sender_password = "your_app_password"
3. Configure SMS (Twilio)

Create account on Twilio

Get:

Account SID

Auth Token

Twilio Phone Number

Replace in code:

account_sid = "ACxxxxxxxx"
auth_token = "your_token"
twilio_number = "+1XXXXXXXXXX"
▶️ Usage

Run the program:

python otp_sender.py

Example:

Enter Email: user@gmail.com
Enter Mobile (+91...): +919876543210
Generated OTP: 483920
📸 Sample Output
✅ OTP sent to Email
✅ OTP sent to Mobile
Enter received OTP: 483920
✅ Verified Successfully
⚠️ Notes

Gmail requires App Password (not normal password)

Twilio free account only works with verified numbers

For testing, SMS can be simulated using print statements
