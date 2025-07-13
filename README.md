# 🌟 Pokémon Explorer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)
![Repo Size](https://img.shields.io/github/repo-size/your-username/pokemon-explorer)
![Last Commit](https://img.shields.io/github/last-commit/your-username/pokemon-explorer)
![Docker](https://img.shields.io/badge/containerized-Docker-blue?logo=docker)
![Traefik](https://img.shields.io/badge/Proxy-Traefik-18A3FF?logo=traefik)
![Status](https://img.shields.io/badge/status-Production--Ready-brightgreen)
![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-orange?logo=html5)
![Nginx](https://img.shields.io/badge/Nginx-Alpine-brightgreen?logo=nginx)

---

Welcome to **Pokémon Explorer** — a containerized static web application that allows you to look up detailed data on any Pokémon between ID #001 and #1000.

Built and maintained by **Lamberto J. Nunez**, this project demonstrates production-ready DevOps workflows, frontend optimization, and Docker-based microservice deployment.

---

## 🚀 Features

- ✨ Query by Pokémon ID (1–1000)  
- 📸 Display official sprites and stats  
- ⚙️ Containerized with **Nginx Alpine**  
- ⚖️ Reverse proxy via **Traefik** (Docker Compose)  
- ⌚ Health checks, restarts, and volume mapping  
- ⚡ Fully offline-static and fast load times  

---

## 📈 Project Screenshots

> *Screenshots coming soon: place `.png` examples like `bulbasaur.png`, `necrozma.png` in `/assets/images` and link below.*

![Screenshot - Home Page](assets/images/home-preview.png)
![Screenshot - Pikachu](assets/images/pikachu-preview.png)

---

## 🚪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/pokemon-explorer.git
cd pokemon-explorer

# Build and start containers
docker-compose up --build

# Visit in browser
http://localhost:8080
