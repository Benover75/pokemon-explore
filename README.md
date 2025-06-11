# 🌟 Pokémon Explorer

Welcome to **Pokémon Explorer** — a containerized static web application that allows you to look up detailed data on any Pokémon between ID #001 and #1000.

Built and maintained by **Lamberto J. Nunez**, this project demonstrates production-ready DevOps workflows, frontend optimization, and Docker-based microservice deployment.

---

## 🚀 Features

* ✨ Query by Pokémon ID (1–1000)
* 📸 Display official sprites and stats
* ⚙️ Containerized with **Nginx Alpine**
* ⚖️ Reverse proxy via **Traefik** (Docker Compose)
* ⌚ Health checks, restarts, and volume mapping
* ⚡ Fully offline-static and fast load times

---

## 📈 Project Screenshots

> *Screenshots coming soon: place `.png` examples like `bulbasaur.png`, `necrozma.png` in `/assets/images` and link below.*

![Screenshot - Home Page](assets/images/home-preview.png)
![Screenshot - Pikachu](assets/images/pikachu-preview.png)

---

## 🚪 How to Run Locally

```bash
# Clone the repo
$ git clone https://github.com/your-username/pokemon-explorer.git
$ cd pokemon-explorer

# Build and start containers
$ docker-compose up --build

# Visit in browser
http://localhost:8080
```

To stop the app:

```bash
$ docker-compose down
```

---

## 🧰 Tech Stack

| Layer         | Technology         |
| ------------- | ------------------ |
| UI/Frontend   | HTML5 + CSS3       |
| Web Server    | Nginx (Alpine)     |
| Proxy Layer   | Traefik v2.10      |
| Orchestration | Docker Compose     |
| Monitoring    | Curl + Healthcheck |

---

## 🔢 Environment Variables

```env
NGINX_HOST=localhost
NGINX_PORT=80
```

---

## 📚 Development Notes

* Ports can be customized in `docker-compose.yml`
* Volume mappings are ideal for logs and static asset debugging
* Optional: Use `.env` for staging/production profiles

---

## 🛌 Deployment Strategy

* ✅ CI/CD-Ready with GitHub Actions (future enhancement)
* 🚨 Easily deployable to services like Render, Fly.io, or AWS EC2
* 🌐 Domain routing with Traefik middleware and rules

---

## ✍️ Author

**Lamberto J. Nunez**
*Computer Science + Data Analytics*
[GitHub](https://github.com/your-username) | [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## ✉️ Contributing

Feel free to fork the repo, create new features, or file an issue. PRs are welcome for feature enhancements or bug fixes.

---

## ⚖️ License

This project is open-sourced under the MIT License. See `LICENSE.md` for details.

---

> “Gotta deploy ’em all! ” — *DevOps Trainer Oak*
