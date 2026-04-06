# push-notification-hub

> Push Notification Hub: Push notification service for iOS/Android with templates

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Audit logging and activity history
- Background jobs for long-running workflows
- Admin analytics dashboard with operational metrics
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway
- Health checks, readiness checks, and structured logging
- Production-oriented environment configuration

## 🧰 Tech Stack
Flutter, Dart, FastAPI, PostgreSQL, Firebase

## 🏗️ Architecture
Three-tier architecture: Flutter, Dart backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/push-notification-hub
cd push-notification-hub

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
