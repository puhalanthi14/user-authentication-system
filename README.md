
# User Authentication System (Node.js + MySQL)

## ✅ Features
- User Registration & Login (JWT based)
- Forgot Password using OTP (Email)
- Profile Update
- Activity Logging (Login, Logout, Password Reset)
- Secure Authentication (Helmet.js, Rate-Limiter)
- Frontend + Backend + MySQL Integration

## 💻 Installation Steps
1. Clone Repository:
   git clone https://github.com/your-repo/auth-system.git
   cd auth-system

2. Install Dependencies:
   npm install

3. Configure .env File:
   PORT=3000
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=your_mysql_password
   DB_NAME=auth_system
   JWT_SECRET=your_jwt_secret
   SMTP_USER=your_email@gmail.com
   SMTP_PASS=your_email_password

4. Start Server:
   node server.js

5. Open Browser:
   http://localhost:3000/frontend/index.html
