#   Node.js-express-mongodb starter 

## 🚀 Features

- ✅ User Signup
- ✅ User Login
- ✅ User Logout
- 🔐 Forgot Password (send code)
- 🔄 Verify Reset Code
- 🔁 Reset Password
- 📩 Email Verification

---

## 🧱 API Endpoints

All routes use the base URL: `{{URL}}`  
Replace `{{URL}}` with your deployed backend URL (e.g., `http://localhost:3000`).

### 🔐 Authentication Routes

| Method | Endpoint                                | Description              |
|--------|-----------------------------------------|--------------------------|
| POST   | `/auth/signup`                          | Register a new user      |
| POST   | `/auth/login`                           | Log in with credentials  |
| GET    | `/auth/logout`                          | Log out the current user |
| POST   | `/auth/forgot-password`                 | Request a reset code     |
| POST   | `/auth/verify-reset-code`               | Verify the code sent     |
| POST   | `/auth/reset-password`                  | Set a new password       |
| POST   | `/auth/verify-email/:token`             | Email verification       |

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- JWT (JSON Web Tokens)
- Nodemailer (for sending email verification and reset codes)
- Postman (for API testing)

---

## 📦 Getting Started

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/Abd-echafi/Node-express-mongoDB-starter.git

cd Node-express-mongoDB-starter

# Install dependencies
npm install
```

## 🔐 Environment Variables
  PORT=3000
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret_key
  EMAIL_USER=your_email_address
  EMAIL_PASS=your_email_password
  CLIENT_URL=http://localhost:3000

# Start in development mode
```bash
npm run dev
```
