# Email Sender (Node.js + Nodemailer)

A simple Node.js project that sends emails through Gmail.

## Requirements

- Node.js 18+ (Node.js 20+ recommended)
- Gmail App Password

## Setup

1. Install dependencies:
```bash
npm install
```

2. Copy `.env.example` and create a `.env` file:
```bash
cp .env.example .env
```

3. Add your own values in `.env`:
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

- `.env` is included in `.gitignore`.
- Never commit sensitive credentials (`EMAIL_PASS`, etc.) to GitHub.
