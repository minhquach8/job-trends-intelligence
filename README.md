# Job Trends Intelligence (NZ)

End-to-end system analysing NZ job market trends: data collection → ML/DL modelling → REST API → React dashboard → AWS deploy.

## High-level
- Frontend: React (Vite + TS + Tailwind + Recharts)
- Backend: Node.js + ExpressJS
- Database: PostgreSQL (AWS RDS)
- AI: Python (pandas, scikit-learn, TensorFlow)
- Cloud: AWS (EC2, S3, RDS, CloudFront, Lambda)
- CI/CD: Docker, GitHub Actions

## Monorepo Layout
- frontend/ — React app
- backend/ — Express REST API
- ai/ — data & ML/DL pipeline
- data/ — local data lake (raw/processed/models)
- infra/ — infra notes & IaC later
- scripts/ — helper scripts
- docs/ — ADRs and design docs
- tests/ — early smoke/health tests

## Getting Started
See docs/adr for decisions. Follow steps in issues or project board.
