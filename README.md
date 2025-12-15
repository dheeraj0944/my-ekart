# 🛒 My eKart Backend
A robust and scalable **Java Spring Boot e-commerce backend** designed to manage products, orders, users, and payments.  
Built for **performance**, **security**, and **flexibility** — ready to integrate with any frontend.

---

## ✨ Features

- **User Management**
  - Secure authentication & authorization (JWT)
  - Role-based access (Admin, Customer)
- **Product Management**
  - Add, update, delete, and list products
  - Category-based filtering and stock tracking
- **Order Processing**
  - Shopping cart & checkout
  - Order tracking & status updates
- **Payment Integration**
  - Payment gateway ready (Razorpay, Stripe, PayPal)
- **Admin Dashboard APIs**
  - Manage products, orders, and customers
- **Database Integration**
  - MySQL with JPA/Hibernate ORM

---

## 🛠 Tech Stack

| Technology     | Purpose                              |
|----------------|--------------------------------------|
| Java 17        | Core backend language                |
| Spring Boot    | Backend framework                    |
| Spring Security| Authentication & Authorization       |
| JWT            | Secure token-based authentication    |
| MySQL          | Relational database                  |
| Hibernate / JPA| ORM for database interaction         |
| Maven          | Build & dependency management        |

---


## 🚀 Getting Started

### 1 Prerequisites
- Java 17 or above
- Maven
- MySQL

### 2 Setup

- # Clone the repository
    - git clone https://github.com/your-username/my-ekart-backend.git
    - cd my-ekart-backend

- # Configure database in src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/ekart_db
spring.datasource.username=root
spring.datasource.password=yourpassword

- # Build & run
  - mvn clean install
  - mvn spring-boot:run


---

## 🔌 API Endpoints

| Method | Endpoint           | Description         | Auth Required |
|--------|--------------------|---------------------|---------------|
| POST   | /api/auth/register | Register new user   | No            |
| POST   | /api/auth/login    | Login user          | No            |
| GET    | /api/products      | List all products   | No            |
| POST   | /api/products      | Add new product     | Yes (Admin)  |
| POST   | /api/orders        | Create order        | Yes (User)   |

---



## 📄 License
This project is licensed under the **MIT License** — you can freely use and modify it.

---

**Author:** Dheeraj R
📧 dheerajr2004@gmail.com
