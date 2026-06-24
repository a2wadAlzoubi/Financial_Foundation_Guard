💰 FinanceGuard – Policy-Driven Financial Management Platform

FinanceGuard is a full-stack financial management system designed to go beyond simple expense tracking by introducing a policy-driven financial governance engine.  
The system enables users to manage transactions, enforce budgeting rules, automate recurring financial operations, and gain insights through analytics and alerts.

---

## 🚀 Project Objective

Most personal finance applications focus only on recording transactions.  
FinanceGuard was built to solve a deeper problem:

> How can users actively control and govern their financial behavior instead of just tracking it?

To solve this, the system introduces:
- Financial Policies
- Automated Rule Evaluation
- Intelligent Alerts
- Recurring Transaction Automation
- Multi-User Financial Collaboration

---

## 🏗 Architecture Overview

The system is built using Clean Architecture + Domain-Driven Design (DDD) principles to ensure scalability, separation of concerns, and maintainability.

### Backend Architecture
- ASP.NET Core Web API
- Clean Architecture (Domain / Application / Infrastructure / API layers)
- Domain-Driven Design (DDD)
- CQRS Pattern (Command Query Responsibility Segregation)
- Repository Pattern
- Specification Pattern
- Background Jobs (Hangfire)

### Frontend Architecture
- Angular (Standalone Components)
- Feature-Based Modular Structure
- Angular Material UI
- Reactive Forms
- Route Guards
- Role-Based UI Rendering

---

## ⚙️ Backend Tech Stack

- ASP.NET Core Web API (.NET)
- Entity Framework Core
- SQL Server
- JWT Authentication & Authorization
- Role-Based Access Control (RBAC)
- Policy-Based Authorization
- Hangfire (Background Processing)
- LINQ & Specifications Pattern
- RESTful API Design

---

## 🎨 Frontend Tech Stack

- Angular
- TypeScript
- Angular Material
- RxJS
- Reactive Forms
- Angular Routing
- HTTP Interceptors
- Guards (Auth / Role-based)
- Chart Integration (Analytics Dashboard)

---

## 🔐 Authentication & Security

- JWT-based Authentication
- Refresh Token Mechanism
- Role-based Authorization (Owner / Member)
- Tenant-level Data Isolation
- Secure API Endpoints

---

## 🧠 Core System Features

### 💳 Transaction Management
- Income and Expense tracking
- Category-based classification
- Filtering and search capabilities
- User-based financial records

---

### 📜 Policy Engine (Core Feature)

FinanceGuard introduces a policy-driven financial control system.

Users can define rules such as:
- Daily spending limits
- Monthly budget limits
- Category-based restrictions

The system evaluates every transaction against these rules and determines:
- Warning level
- Critical violations
- Policy breaches

---

### 🔁 Recurring Transactions
Automated financial operations using background jobs:
- Subscriptions (Netflix, Spotify)
- Salary income
- Rent payments
- Utility bills

Executed automatically using Hangfire scheduling.

---

### 🚨 Intelligent Alerts System
The system generates alerts when:
- Spending approaches defined limits
- Budget is exceeded
- Policy violations occur

Alert types include:
- Warning
- Critical

---

### 📊 Financial Analytics
Interactive dashboards providing:
- Spending distribution by category
- Monthly financial trends
- Budget utilization overview
- Financial summaries

---

### 👥 Multi-User & Multi-Tenant Support
- Owner & Member roles
- Tenant-based isolation
- Secure data separation between users

---

## 🧩 System Modules

- Authentication Module
- Transactions Module
- Policies Module
- Recurring Module
- Alerts Module
- Reports & Analytics Module
- Users Management Module

---

## 📦 Backend Design Patterns Used

- Clean Architecture
- CQRS
- Repository Pattern
- Specification Pattern
- Dependency Injection
- Middleware Pipeline
- Background Job Processing

---

## 📈 Key Engineering Highlights
[6/24/2026 5:18 AM] Awad Alzo'ubi: - Designed a custom Policy Evaluation Engine
- Implemented automated financial rule processing
- Built background-driven recurring transaction system
- Designed scalable multi-tenant architecture
- Implemented role-based secure system access

---

## 🖥 Frontend Highlights

- Modular feature-based architecture
- Reusable UI components
- Role-based UI rendering
- Dynamic dashboards
- Responsive Angular Material design

---

## 📚 What I Learned

This project strengthened my understanding of:

- System design and software architecture
- Domain modeling for financial systems
- Full-stack integration (Angular + ASP.NET Core)
- Scalable backend design principles
- Business rule engine implementation
- Background processing systems

---

## 📌 Future Improvements

- Event-Driven Architecture (Kafka/RabbitMQ)
- Microservices migration
- Advanced AI-based financial recommendations
- Mobile application (Flutter/React Native)
- Real-time notifications (SignalR)

---

## 🛠 Setup Instructions

### Backend
`bash
dotnet restore
dotnet run
