# Keep Green &mdash; Houseplant Management Ecosystem 🌿

**Keep Green** is a full-scale, value-driven software product designed to streamline and optimize indoor plant cultivation, environmental tracking, and resource management. The ecosystem is built from scratch utilizing modern enterprise patterns and containerized cloud environments.

🌐 **Live Demo:** [https://keepgreen.ecollow.com](https://keepgreen.ecollow.com)  
🔒 *Note: The core source code of this repository is kept private for commercial and intellectual property protection. This repository serves as an architectural blueprint and public technical overview.*

---

## 🏗️ Architectural Blueprint & Patterns

The application is engineered with a strong emphasis on testability, maintainability, and strict separation of concerns, utilizing the following paradigms:

* **Clean Architecture:** Divided into decoupled layers (Domain, Application, Infrastructure, and Presentation/UI) ensuring that core business logic remains independent of databases, frameworks, or external tools.
* **Domain-Driven Design (DDD):** Business rules are encapsulated within rich domain entities, aggregates, and value objects, maintaining a robust domain model.
* **CQRS (Command Query Responsibility Segregation):** Separates read operations from write operations via explicit commands and queries, maximizing throughput, scalability, and clarity.
* **Result Pattern:** Business failures, validation issues, and operational bottlenecks are handled explicitly using a strict functional `Result` flow rather than relying on heavy and unpredictable `try-catch` exception throwing.

---

## 🛠️ Technology Stack

* **Backend Core:** C# / .NET 8 & .NET 9, ASP.NET Core Web API
* **Database & ORM:** PostgreSQL / Entity Framework Core (highly optimized relational queries, indexing, and data migrations)
* **Frontend UI:** Blazor (Rich reactive interfaces designed for both seamless desktop and mobile interactions)
* **DevOps & Hosting:** Full Docker containerization, automated multi-container deployment, running securely in an isolated environment

---

## 📈 System Features Under Active Development

* **Automated Telemetry:** Real-time data processing from environmental sensors.
* **Smart Notification Pipelines:** Intelligent triggers and alerts based on historical plant health patterns.
* **Localization Ecosystem:** Full multi-language translation architecture natively built-in.
