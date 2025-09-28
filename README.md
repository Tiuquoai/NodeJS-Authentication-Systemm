# NodeJS Authentication System

Ứng dụng **Authentication System** với các chức năng cơ bản:
- Đăng nhập bằng tài khoản nội bộ
- Đăng nhập với Google OAuth 2.0
- Đăng xuất
- Quên mật khẩu (reset password)
- Tích hợp Google reCAPTCHA
- Gửi email (NodeMailer)

---

## Công nghệ sử dụng
- **Node.js** + **Express**
- **MongoDB** + **Mongoose**
- **Passport.js** (Local Strategy, Google OAuth)
- **Nodemailer**
- **Google reCAPTCHA**


---

## Chạy ứng dụng

```bash
# Cài dependencies
npm install

# Chạy dev với nodemon
npm start
```

Mở trình duyệt tại:  `http://localhost:3000`

---

## Demo giao diện

### 1. Đăng nhập
![Sign In](https://raw.githubusercontent.com/Tiuquoai/NodeJS-Authentication-Systemm/main/results/signin.png)

### 2. Đăng nhập với Google
![Google Sign In](https://raw.githubusercontent.com/Tiuquoai/NodeJS-Authentication-Systemm/main/results/sign_gg.png)  
![Google Sign In (Step 2)](https://raw.githubusercontent.com/Tiuquoai/NodeJS-Authentication-Systemm/main/results/sign_gg1.png)

### 3. Quên mật khẩu
![Forgot Password](https://raw.githubusercontent.com/Tiuquoai/NodeJS-Authentication-Systemm/main/results/forgot_pw.png)

### 4. Đăng xuất
![Logout](https://raw.githubusercontent.com/Tiuquoai/NodeJS-Authentication-Systemm/main/results/logout.png)

---
