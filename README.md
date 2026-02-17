# 🏦 CryptoFlow

> Real-time cryptocurrency monitoring platform built with microservices architecture

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java 17, Spring Boot 3.x, Spring Batch |
| Messaging | Apache Kafka |
| Database | PostgreSQL 16 |
| Frontend | Angular 17 |
| Infrastructure | Docker, Docker Compose, GitHub Actions |

## Architecture
```
XML Feeds → MS-Batch → Kafka → MS-Price-Enricher → MS-Alert-Engine → PostgreSQL → REST API → Angular
```

## Getting Started
```bash
git clone https://github.com/TU_USUARIO/cryptoflow.git
cd cryptoflow
docker-compose up
```

## Services

| Service | Port | Description |
|---------|------|-------------|
| ms-api | 8080 | REST API + Swagger UI |
| frontend-angular | 4200 | DataTable view |

## Author
**Gian** — Backend Developer
