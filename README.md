# Pokémon Explorer

This project is a containerized static site for Pokémon Explorer, served by Nginx on Alpine Linux, with Traefik as a reverse proxy for routing.

## Features
- Lightweight Nginx container serving static assets on port 8000
- Traefik for edge routing and HTTPS management
- Healthchecks for container readiness
- Docker Compose orchestration for development and production readiness

## Usage

```bash
docker-compose up --build -d
