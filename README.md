# 📬 XKCD Email Subscription System

A PHP-based email verification and subscription system that delivers a random [XKCD](https://xkcd.com/) comic every 24 hours to registered users via email. Built with vanilla PHP, file-based storage, and automated using CRON. Includes a secure email verification flow and unsubscribe mechanism.

---

## 🚀 Features

- ✅ Email registration with 6-digit code verification
- 📩 Daily XKCD comic emails sent in HTML format
- 🔁 Automatic CRON job to fetch and send comics
- ❌ Secure unsubscribe flow with confirmation code
- 🧾 File-based storage (no database required)
- 🛠 PHPMailer + Gmail SMTP integration
- 🧪 Logs for email and CRON execution
