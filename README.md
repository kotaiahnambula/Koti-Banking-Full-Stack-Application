🏦 Koti-Bank

Koti-Bank is a 🏦 banking application built with 🌱 Spring Boot 3 Microservices (Java 17 backend) and ⚡ Angular (frontend).
It demonstrates real-world enterprise app patterns such as 🏗 microservices architecture, 🚪 API Gateway, 🔍 service discovery, and 🔐 secure authentication.

🚀 Features

🔑 User Authentication (JWT/OAuth2 with Spring Security)

👤 Customer Management (Register, Login, Profile)

💳 Accounts Service (Create & Manage Bank Accounts)

💸 Transactions Service (Deposit, Withdraw, Transfer)

📜 Transaction History (View past operations)

⚙️ Microservices Infrastructure (Eureka, Config Server, API Gateway)

🖥 Angular Frontend with dashboard, accounts & transactions

🛠️ Tech Stack

Backend:

☕ Java 17

🌱 Spring Boot 3.x

☁️ Spring Cloud (Eureka, Config, Gateway, Resilience4j)

🔐 Spring Security (JWT/OAuth2)

🗄 JPA/Hibernate

🛢 MySQL/PostgreSQL

🧩 Redis (caching)

🐳 Docker

Frontend:

⚡ Angular 16+

📡 RxJS

🎨 Bootstrap / Tailwind CSS

DevOps & Tools:

🐳 Docker Compose

☸️ Kubernetes (future enhancement)

⚙️ GitHub Actions (CI/CD)

📦 Maven Wrapper

📂 Repository Structure
Koti-Bank/
├── backend/               🏗 Spring Boot Microservices
│   ├── account-service/    💳
│   ├── transaction-service/💸
│   ├── user-service/       👤
│   ├── api-gateway/        🚪
│   ├── discovery-server/   🔍
│   └── config-server/      ⚙️
├── frontend/              🖥 Angular App
├── docs/                  📖 Documentation & diagrams
└── docker-compose.yml     🐳 Local setup
