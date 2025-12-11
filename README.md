# AWS Issue Tracking Web Application
A cloud-native, serverless issue tracking system built with AWS services. This project demonstrates full SDLC documentation, AWS architecture, CI/CD planning, and PM-level delivery capability.


## Features
- User authentication (Cognito)
- Issue creation, assignment, updates
- Commenting and file attachments (S3)
- Dashboard metrics
- Admin role support
- REST API via API Gateway + Lambda
- PostgreSQL database (RDS)
- Fully documented SDLC


## Cloud Architecture (Simplified)
React (S3 + CloudFront)
→ API Gateway
→ Lambda backend
→ RDS PostgreSQL
→ S3 for attachments
→ CloudWatch monitoring


## Folders
- `docs/` – Full SDLC documentation
- `architecture/` – Diagrams and system overview
- `infrastructure/` – Terraform templates
- `frontend/` – React UI (placeholder for now)
- `backend/` – API code (placeholder for now)


## Status
This is a portfolio project demonstrating cloud project delivery, system design, and SDLC documentation.
