# Inventory Management System API

A high-performance, asynchronous RESTful API built with **ASP.NET Core 10** following **Clean Architecture** and **Domain-Driven Design (DDD)** principles. Designed with an emphasis on strict separation of concerns, high-efficiency data handling, and optimized developer experience (DX).

## 🏗️ Architecture Overview

This project uses a four-layer Clean Architecture structure to keep the core business logic completely independent of external frameworks, databases, and UI choices.

* **Domain:** Contains enterprise business rules, entities, value objects, and domain exceptions. (Zero external dependencies).
* **Application:** Orchestrates application use cases using CQRS (via MediatR), input validation, and core abstractions.
* **Infrastructure:** Handles data persistence (EF Core 10), migrations, external API integrations, and infrastructure services.
* **API:** A lightweight presentation layer leveraging ASP.NET Core Minimal APIs for ultra-low overhead endpoints.

## 🛠️ Tech Stack & Patterns

* **Runtime:** .NET 10 SDK
* **Framework:** ASP.NET Core APIs
* **ORM:** Entity Framework Core 10
* **Design Patterns:** CQRS (Command Query Responsibility Segregation), Repository/Unit of Work, Domain Events
* **Tooling:** FluentValidation, MediatR

## 🚀 Getting Started

### Prerequisites
* .NET 10 SDK installed
* A localized Database engine or configured connection string

### Installation & Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/genbadar/inventory-management-api.git](https://github.com/genbadar/inventory-management-api.git)
   cd inventory-management-api
   
