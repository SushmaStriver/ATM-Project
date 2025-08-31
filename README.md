# \# ATM Project 💳

# 

# A Spring Boot project that simulates an ATM system with OTP verification for secure withdrawals.

# 

# \## 🚀 Features

- Check account balance  

- Deposit money  

- Withdraw money (with OTP verification if amount > 5000)  

- OTP delivery via SMS or Email  

# 

# \## 📌 Example Endpoints

#\- \*\*Check Balance\*\* → `GET /atm/balance/{id}`  

 \- \*\*Withdraw Money\*\* → `POST /atm/withdraw?id=1\&amount=2000\&choice=2\&contact=email`  

\- \*\*Verify OTP\*\* → `POST /atm/verifyOtp?id=1\&contact=email\&otp=123456\&amount=7000`  

\- \*\*Deposit Money\*\* → `POST /atm/deposit?id=1\&amount=5000`  

# 

#  🛠 Tech Stack

 \- Java 21  

\- Spring Boot 3  

 \- MySQL (for storing accounts)  

 \- Twilio (for SMS OTP)  

 \- JavaMailSender (for email OTP)  

# 

# \## 📂 How to Run

 1\. Clone the repo  

&nbsp;  ```bash

 &nbsp;  git clone https://github.com/SushmaStriver/ATM-Project.git

&nbsp;  cd ATM-Project

 ATM Project

