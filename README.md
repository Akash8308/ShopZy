# 🛒 ShopZy - Domain-Driven Full Stack E-Commerce Platform

ShopZy is a **full-stack e-commerce application** built using **Domain-Driven Design (DDD)** principles. It simulates real-world online shopping workflows including product browsing, cart management, order processing, and secure authentication using JWT and OAuth2 (Google & GitHub).

The system is designed with scalability, maintainability, and clean domain separation in mind, making it suitable for production-level backend systems and future microservices migration.

---

## 🚀 Project Overview

ShopZy is a **DDD-based backend platform** that manages core e-commerce operations across multiple bounded contexts:

- User Management
- Product Catalog
- Shopping Cart
- Order Processing
- Authentication & Authorization

The system is designed to be **modular, extensible, and cloud-ready**.

---

## 🧩 Architecture & Design

### 🏛️ Domain-Driven Design (DDD)

The project is structured around **bounded contexts**, ensuring each business domain is independent and self-contained:

- **User Domain**
- **Catalog Domain**
- **Cart Domain**
- **Order Domain**

Each domain contains its own:
- Controller
- Service
- Repository
- Domain Models (Aggregates, Entities)

### 📦 Key Design Principles

- Domain-Driven Design (DDD)
- SOLID Principles
- Clean Architecture principles
- Separation of Concerns
- Stateless authentication (JWT)

---

## 🔐 Security

ShopZy implements **enterprise-grade authentication and authorization**:

- JWT-based stateless authentication
- OAuth2 login (Google & GitHub)
- Spring Security filter chain
- Role-Based Access Control (USER / ADMIN)
- BCrypt password encryption

---

## 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven

### Authentication
- JWT (JSON Web Tokens)
- OAuth2 (Google, GitHub)

### Frontend
- Angular / AngularJS

---

## 📦 Project Structure (DDD-Based)
