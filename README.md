# Email Sender (Node.js + Nodemailer)

Simple Node.js loyiha: Gmail orqali email yuboradi.

## Requirements

- Node.js 18+ (yoki 20+ tavsiya)
- Gmail App Password

## Setup

1. Dependency o'rnating:
```bash
npm install
```

2. `.env.example` dan nusxa olib `.env` yarating:
```bash
cp .env.example .env
```

3. `.env` ichiga o'zingizning qiymatlarni kiriting:
```env
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
EMAIL_TO=receiver@gmail.com
EMAIL_SUBJECT=Hello from Nodemailer
EMAIL_TEXT=This is a test email sent using Nodemailer.
```

4. Loyihani ishga tushiring:
```bash
npm start
```

## Security

- `.env` fayli `.gitignore`ga qo'shilgan.
- Maxfiy ma'lumotlarni (`EMAIL_PASS` va boshqalar) GitHub'ga joylamang.
