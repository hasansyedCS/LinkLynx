# LinkLynx

[![Portfolio](https://img.shields.io/badge/Portfolio-hasansyed.dev-blue)](https://hasansyed.dev)
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF)](https://github.com/hasansyedCS/hasansyed.dev/actions)
[![Terraform](https://img.shields.io/badge/IaC-Terraform-623CE4)](https://github.com/hasansyedCS/hasansyed.dev/tree/main/infrastructure)
[![AWS](https://img.shields.io/badge/AWS-SAA--C03-orange)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)

URL shortener built on REST API with FastAPI, PostgreSQL, Redis, and Docker.

---

## Overview

LinkLynx is a production-grade URL shortening service with click analytics. It's built as a containerized REST API that:

- Shortens long URLs into compact, shareable links (e.g., `linklynx.hasansyed.dev/abc123`)
- Tracks click analytics (count, timestamp, referrer) for each shortened link
- Uses **FastAPI** for high-performance async API endpoints
- Persists data with **PostgreSQL** and caches frequently accessed links with **Redis**
- Is containerized with **Docker** for consistent local development and production deployment
- Is managed as **infrastructure as code** with Terraform
- Targets **AWS ECS Fargate** for serverless container deployment

### Tech Stack

| Layer | Technology |
|-------|------------|
| API Framework | FastAPI (Python) |
| Database | PostgreSQL (AWS RDS) |
| Cache | Redis (AWS ElastiCache) |
| Container | Docker |
| Orchestration | AWS ECS Fargate |
| Infrastructure | Terraform |
| CI/CD | GitHub Actions |

### Current Status

🚧 **MVP in active development** – Core shortening and redirect working. Click analytics, Redis caching, and AWS deployment in progress.

## Connect

- Live: [https://hasansyed.dev](https://hasansyed.dev)
- GitHub: [https://github.com/hasansyedCS](https://github.com/hasansyedCS)
- LinkedIn: [https://linkedin.com/in/hasansyedCS](https://linkedin.com/in/hasansyedCS)