# ADR 0001: Project scope and high-level architecture
Date: 2025-10-25
Status: Accepted

## Context
We need an end-to-end system to analyse NZ job market trends using a React frontend, ExpressJS backend, PostgreSQL, and Python ML/DL.

## Decision
Adopt a monorepo with `frontend/`, `backend/`, `ai/`, and shared infra/docs/tests. Use AWS (EC2/S3/RDS/CloudFront/Lambda) for deployment.

## Consequences
- Clear separation of concerns.
- Easier portfolio demonstration.
- CI/CD can target each part independently.
