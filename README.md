# 🛒 High-Performance E-Commerce Engine (Full-Stack)

[![Status](https://img.shields.io/badge/Status-In--Progress-orange)]()
[![Framework](https://img.shields.io/badge/.NET-8.0-blue)]()
[![Frontend](https://img.shields.io/badge/Angular-17-red)]()

A modern, decoupled e-commerce platform built from the ground up, focusing on **Scalability**, **Clean Architecture**, and **Advanced State Management**.

## 🏗️ Architectural Overview (Clean/Onion Architecture)
The project is structured into distinct layers to ensure separation of concerns:
- **Core (Domain & Application):** Contains entities, interfaces, and business logic.
- **Infrastructure:** Handles data persistence (EF Core) and external services.
- **API:** RESTful endpoints with unified response structures.

## 🛠️ Key Technical Achievements

### 🔹 Backend Excellence
- **Clean Architecture (Onion):** Ensuring the system is independent of UI, Database, or any external agency.
- **Advanced Patterns:** Implementation of **Repository Pattern** and **Unit of Work** for transaction integrity.
- **Generic Data Pagination:** Designed a robust `Pagination<T>` container using `IReadOnlyList<T>` for type-safe API responses.
- **Global Exception Handling:** Custom Middleware to intercept exceptions and return structured responses.
- **Automated Mapping:** Using **AutoMapper** and **DTOs** to decouple domain entities from API contracts.

### 🔹 Frontend Sophistication (Angular 17)
- **Reactive UI:** Leveraging **RxJS Services** for asynchronous data streams.
- **Type-Safe Interfaces:** Ensuring strict typing across the entire frontend application.
- **Client-Side State:** A custom-built **Cart System** utilizing Local Storage for a persistent, reactive experience.

## 🚀 Upcoming Milestones (Roadmap)
- [ ] **Security:** Secure Identity Management via JWT & Refresh Tokens.
- [ ] **Payments:** Full payment lifecycle integration with **Stripe API & Webhooks**.
- [ ] **Real-time:** Order status tracking and notifications.

## 📸 Project Teasers (Work in Progress)
*(Add your current screenshots here to show the progress of the UI)*

---
📂 **Backend Repo:** [Click Here](https://github.com/Ibrahem-Tabaneh/ECommerce-Asp.netCore-Angular-CleanArch)  
📂 **Frontend Repo:** [Click Here](https://github.com/Ibrahem-Tabaneh/Ecommerce3)

📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/ibrahem-tabaneh-249683249)
