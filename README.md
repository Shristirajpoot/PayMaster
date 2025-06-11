# 💳 PayMaster – Seamless PayPal Integration for Laravel

![GitHub stars](https://img.shields.io/github/stars/Shristirajpoot/PayMaster?style=social)
![Last commit](https://img.shields.io/github/last-commit/Shristirajpoot/PayMaster?color=brightgreen)
![Laravel](https://img.shields.io/badge/Built%20with-Laravel-red)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📌 Overview

**PayMaster** is a Laravel-based application that demonstrates a clean and secure **PayPal payment gateway integration**.  
Ideal for developers looking to quickly add payment functionality into their Laravel web applications.

---

## 🎯 Features

- 🔐 **Secure PayPal SDK Integration**  
- ⚡ **Quick Transaction Testing** in development environment  
- 💬 **Real-time Payment Feedback** with transaction status  
- 🧪 **Test-ready** Laravel structure  
- 🎥 **Live Demo**: [Watch on YouTube](https://www.youtube.com/watch?v=WOsXayVmnoc)  
- 📚 **Tutorial Reference**: [JustLaravel.com](http://justlaravel.com/paypal-payment-gateway-integration-laravel/)

---

## ⚙️ Technologies Used

- Laravel (PHP Framework)
- PayPal REST API
- Composer, PHP, MySQL
- Bootstrap (for UI components)

---

## 📂 Project Structure
```
PayMaster/
├── app/ # Core application logic
├── bootstrap/ # Laravel bootstrap files
├── config/ # Configuration files
├── database/ # Migrations & seeds
├── public/ # Public assets (entry point)
├── resources/ # Blade templates and views
├── routes/ # Web routes
├── tests/ # PHPUnit tests
├── .env.example # Environment config example
├── composer.json # PHP dependencies
├── README.md # This file
```


---

## 🚀 Getting Started

### 📦 Prerequisites

- PHP 7.4+  
- Composer  
- Laravel CLI  
- MySQL  
- PayPal Developer Account (for CLIENT_ID & SECRET)

### 🔧 Installation Steps

1. Clone the repository  
   ```bash
   git clone https://github.com/Shristirajpoot/PayMaster.git
   cd PayMaster
   ```
2. Install dependencies

```bash

composer install
composer update
```
3. Rename .env.example to .env

```bash

cp .env.example .env
```
4. Add your PayPal credentials (CLIENT_ID and SECRET) to the .env file

5. Generate application key

```bash
php artisan key:generate
```
6. Start the Laravel server

```bash
php artisan serve
```
7. Test the payment flow in browser

## 📤 Example PayPal Response

```json

{
  "id": "PAYID-123456",
  "status": "COMPLETED",
  "payer": {
    "email": "test@example.com"
  },
  "amount": {
    "currency_code": "USD",
    "value": "25.00"
  }
}
```
## 💡 Tips
- Use PayPal Sandbox mode for safe testing

- Ensure .env variables are correct

- Laravel logs helpful errors in storage/logs/

## 🤝 Contributing
Contributions are welcome!
If you spot a bug or have a feature request, please open an issue or pull request.

Steps:

```bash
fork → clone → create feature branch → commit → push → open PR
```
---
## 👩‍💻 Author
### Shristi Rajpoot
- 📧 Email: shristirajpoot369@gmail.com
- 🔗 GitHub: @Shristirajpoot

---

## 📜 License
Distributed under the **MIT License** — see [`LICENSE`](./LICENSE).

---

### ⭐ Like what you see? **Star** the repo, fork it, or open an issue — contributions welcome!
