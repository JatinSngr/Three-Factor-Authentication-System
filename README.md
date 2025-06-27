Three-Factor-Authentication-System
# 🔐 Three Factor Authentication System Against Cyber Attacks

This project is a secure user authentication system developed using Python and web technologies, designed to defend against unauthorized access and common cyber threats. It implements **three layers of authentication** to ensure only verified users can log in.

## 🔧 Features

- ✅ **Registration Phase**:  
  - User signs up with credentials and answers three security questions:
    1. Which city were you born in?  
    2. Name of your first school?  
    3. Your pet's name?

- 🔐 **Login Phase (Three-Step Authentication)**:  
  1. Password verification  
  2. OTP sent to registered email (via SMTP)  
  3. Correct answers to all three security questions

- 🛡️ Protects against brute-force attacks, phishing, and unauthorized logins

## 🛠️ Technologies Used

- **Backend**: Python  
- **Frontend**: HTML, CSS, JavaScript  
- **Email Service**: SMTP (for OTP delivery)  
- **Database**: MySQL / SQLite (for user data and questions)

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/JatinSngr/three-factor-auth-system.git
   cd three-factor-auth-system
