# Architecture

Anapurna is organized as a monorepo:

- Next.js frontend
- Spring Boot modular monolith for core business logic
- FastAPI recommendation service
- PostgreSQL as the primary relational database
- Redis for caching
- S3 for media storage
- SQS for asynchronous events when introduced
- Terraform for AWS infrastructure
