# 🚀 Laravel REST API Pro

Production-ready RESTful API built with Laravel.  
Includes JWT authentication, secure architecture

---

## 📌 Overview

Laravel REST API Pro is a clean and scalable backend starter project designed for real-world applications.  
It follows best practices including MVC architecture, API Resources, Form Requests validation, and JWT-based authentication.

This project is ideal for:

- SaaS backends
- Mobile app APIs
- Admin dashboards
- MVP development
- Production-ready API starter template

---

## ⚙️ Tech Stack

- Laravel 10+
- PHP 8.1+
- MySQL
- JWT Authentication
- RESTful API Architecture

---

## ✨ Features

✅ JWT Authentication (Register / Login / Logout)  
✅ Protected API Routes  
✅ Full CRUD (Posts Module Example)  
✅ Form Request Validation  
✅ API Resource Formatting  
✅ Clean MVC Structure  
✅ Secure Password Hashing  
✅ Scalable & Production-Ready Structure  

---

## 📂 Project Structure

```
app/
 ├── Http/
 │    ├── Controllers/Api
 │    ├── Requests
 │    ├── Resources
 ├── Models
routes/
 ├── api.php
```

---

## 🔐 Authentication Flow

1. User registers
2. User logs in
3. API returns JWT token
4. Token is used in Authorization header

```
Authorization: Bearer YOUR_TOKEN
```

---

## 📡 API Endpoints

### 🔑 Auth Routes

| Method | Endpoint | Description |
|--------|----------|------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login user |
| GET | /api/profile | Get logged-in user |
| POST | /api/logout | Logout user |

---

### 📝 Posts (Protected Routes)

| Method | Endpoint | Description |
|--------|----------|------------|
| GET | /api/posts | Get all posts |
| POST | /api/posts | Create post |
| GET | /api/posts/{id} | Show single post |
| PUT | /api/posts/{id} | Update post |
| DELETE | /api/posts/{id} | Delete post |

---

## 🛠 Installation Guide

Clone the repository:

```bash
git clone https://github.com/yourusername/laravel-rest-api-starter.git
cd laravel-rest-api-starter\
```

Install dependencies:

```bash
composer install
```

Copy environment file:

```bash
cp .env.example .env
```

Generate app key:

```bash
php artisan key:generate
```

Generate JWT secret:

```bash
php artisan jwt:secret
```

Configure your database inside `.env` file.

Run migrations:

```bash
php artisan migrate
```

Start server:

```bash
php artisan serve
```

API will run at:

```
http://127.0.0.1:8000/api
```

---

## 🧪 Testing API

You can test endpoints using:

- Postman
- Thunder Client (VS Code)
- cURL

---

## 📈 Production Ready Improvements

You can extend this project with:

- Role & Permission System
- API Documentation (Swagger)
- Docker Setup
- Unit Testing
- Rate Limiting
- CI/CD Pipeline

---

## 🤝 Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-sourced software licensed under the MIT license.

---

## 👨‍💻 Author

Developed by **Your Name**

If you like this project, consider giving it a ⭐ on GitHub.