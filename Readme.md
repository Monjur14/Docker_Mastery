# 🐳 Docker Mastery

A free, interactive, browser-based learning tracker for mastering Docker — from your first `hello-world` container all the way to multi-architecture builds and CI/CD pipelines. No backend, no accounts, no cost.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Features

- **43 hands-on tasks** organized across three progressive skill levels
- **Progress tracking** — check off tasks as you complete them; state persists in `localStorage`
- **Live progress bar** with task counters (done / remaining / percentage)
- **Filter view** by level (Beginner / Intermediate / Advanced), completed, or remaining tasks
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript; no build step required
- **Responsive design** — works on desktop and mobile
- **Dark theme** with a clean developer-focused aesthetic

---

## Roadmap Structure

| Level | Tasks | What You'll Learn |
|---|---|---|
| 🟢 **Beginner** | 1 – 13 | Core CLI, images, containers, ports, logs, interactive shells |
| 🔵 **Intermediate** | 14 – 30 | Dockerfiles, volumes, networking, databases, Docker Compose |
| 🔴 **Advanced** | 31 – 43 | Multistage builds, security hardening, CI/CD, VPS deployment, Buildx |

### Beginner (Tasks 1–13)
Getting comfortable with the Docker CLI and core concepts.

- Run your first container and understand the image pull flow
- Map ports, inspect metadata, stream logs
- Manage the container lifecycle (stop / start / restart / remove)
- Pull and explore official images from Docker Hub
- Copy files into and out of running containers

### Intermediate (Tasks 14–30)
Writing Dockerfiles and building real multi-container applications.

- Author Dockerfiles for Node.js apps with proper layering
- Tag, version, and push images to Docker Hub
- Persist data with named volumes and bind mounts
- Connect containers over user-defined bridge networks
- Orchestrate multi-service stacks with Docker Compose

### Advanced (Tasks 31–43)
Production-ready Docker skills used in professional environments.

- Shrink image sizes with multistage builds
- Enforce resource limits and container health checks
- Harden containers: non-root users, Seccomp profiles, secrets management
- Scan images for CVEs with Docker Scout / Trivy
- Build multi-architecture images with `docker buildx`
- Automate builds and deployments with GitHub Actions

---

## Getting Started

No installation required. The project is a single self-contained HTML file.

### Option 1 — Open directly in your browser

```bash
git clone https://github.com/your-username/docker-mastery-roadmap.git
cd docker-mastery-roadmap
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

### Option 2 — Serve locally (recommended for full link support)

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .

# Then visit http://localhost:8080
```

### Option 3 — Deploy to GitHub Pages

1. Fork this repository
2. Go to **Settings → Pages**
3. Set the source branch to `main` and folder to `/ (root)`
4. Your roadmap will be live at `https://your-username.github.io/docker-mastery-roadmap`

---

## 📁 Project Structure

```
docker-mastery-roadmap/
├── index.html          # Main roadmap tracker (self-contained)
├── assets/
│   └── docker.png      # Favicon
├── task1.html          # Individual task pages (hands-on instructions)
├── task2.html
├── ...
└── task43.html
```

Each `taskN.html` page contains detailed instructions, commands, and expected output for that specific task.

---

## 🤝 Contributing

Contributions are welcome! Here's how to get involved:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feat/your-improvement`
3. **Commit** your changes: `git commit -m "feat: add task page for task 14"`
4. **Push** to your branch: `git push origin feat/your-improvement`
5. **Open a Pull Request** with a clear description of what you changed and why

### Ideas for contributions

- Write or improve individual task pages (`task1.html` … `task43.html`)
- Add new tasks or suggest edits to existing goals
- Improve mobile responsiveness or accessibility
- Add a print / export-to-PDF feature
- Translate task content to other languages
- Add a "notes" field per task for personal annotations

Please open an issue first for any significant changes so we can discuss the approach.

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 (custom properties) | Theming, layout, responsive design |
| Vanilla JavaScript (ES6+) | Task state management, filtering, rendering |
| `localStorage` | Persistent progress — no server needed |

No frameworks. No bundlers. No build step. Just open and use.

---

## Acknowledgements

- [Docker Documentation](https://docs.docker.com) — the authoritative reference behind every task
- [Docker Hub](https://hub.docker.com) — the image registry used throughout the roadmap
- The open-source community for making containerization knowledge freely available

---

<p align="center">
  Built with ❤️ for the developer community · If this helped you, consider giving it a ⭐
</p>