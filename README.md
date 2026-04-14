# 🛒 High-Performance E-Commerce Engine (Backend)

[![Status](https://img.shields.io/badge/Status-In--Progress-orange)]()
[![Framework](https://img.shields.io/badge/.NET-8.0-blue)]()
[![Architecture](https://img.shields.io/badge/Architecture-Clean--Onion-green)]()

A modern, decoupled e-commerce API built with **.NET 8**, focusing on **Scalability**, **Clean Architecture**, and **High-Performance Data Querying**.

## 🏗️ Architectural Overview
The project follows a modular layered approach:
- **Core (Domain & Application):** Defines the central entities and system interfaces.
- **Infrastructure:** The logic engine, containing **Business Logic**, Data Persistence (EF Core), and Repository implementations.
- **API (Web Layer):** Managing RESTful endpoints and containing **DTOs** (Data Transfer Objects) to secure and abstract internal models.

## 🛠️ Completed Achievements ✅

- **Catalog & Product Intelligence:** - Full implementation of the product catalog with dedicated endpoints for **Product Details**.
  - Integrated **Filtering by Price** and multi-criteria **Searching** by Category or Name.
- **Dynamic Query Engine:** - Server-side sorting and **Generic Pagination** using `IReadOnlyList<T>` for optimized response times.
- **Persistent Cart Logic (Client-Side):** - Designed the API to support a reactive **Client-Side Cart system** where users can Add/Remove/Update items, persisted via **Local Storage** on the frontend.

## ⚙️ Technical Highlights
- **Repository Pattern & Unit of Work:** Ensuring clean data access and transaction integrity.
- **AutoMapper:** Seamlessly mapping Domain Entities to API-level DTOs.
- **Global Middleware:** Centralized exception handling for structured error responses.

## 📸 API Documentation & Testing (Swagger)

<div align="center">
  <img src="رابط_صورة_سواجر_1" width="48%" alt="API Endpoints" />
  <img src="رابط_صورة_الاستجابة" width="48%" alt="JSON DTO Response" />
</div>

## 🚀 Upcoming Milestones
- [ ] **Security:** Secure Identity Management via JWT & Refresh Tokens.
- [ ] **Payments:** Full payment lifecycle integration with **Stripe API & Webhooks**.

---
📂 **Frontend Repo:** [View Angular Project](رابط_مستودع_الفرونت)  
📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/ibrahem-tabaneh-249683249)
