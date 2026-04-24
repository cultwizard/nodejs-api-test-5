# Node.js API - Test Case 5 (CI/CD Pipeline)

This repository contains the complete implementation for Test Case 5, featuring a Node.js API, Docker containerization, and a GitHub Actions CI/CD pipeline.

## Features
- **Node.js API**: Express server with a `/health` endpoint.
- **Docker**: Containerized deployment via `Dockerfile` and `docker-compose.yml`.
- **CI/CD Pipeline**:
  - Located in `.github/workflows/deploy.yml`.
  - Triggers automatically on push to the `main` branch.
  - Checks out the code, sets up Node.js 18, installs dependencies, builds the Docker image, and simulates deployment.
