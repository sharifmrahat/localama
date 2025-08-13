# 📚 Project Documentation

Welcome to the official documentation for **Your Project Name**.  
This guide will walk you through installation, running the app, and contributing.

---

## 📦 Installation Guidelines

### 1️⃣ Install and Run Ollama

- Install Ollama in your machine from: https://ollama.com/

### 2️⃣ Download Model

- Download model: https://ollama.com/search
- Note: You should have at least 8 GB of RAM available to run the 7B models, 16 GB to run the 13B models, and 32 GB to run the 33B models.

```bash
ollama pull <model-name>
```

- Check available models:

```bash
ollama list
```

## 🖥️ Running the Application

### Manual Setup

- Run the Frontend and Backend separately after cloning from GitHub.
- Backend:

```bash
git clone https://github.com/sharifmrahat/localama-api.git
cd localama-api
npm install
npm run start:dev
```

- Frontend:

```bash
git clone https://github.com/sharifmrahat/localama-fe.git
cd localama-fe
bun install
bun run dev
```

### Docker Setup

- Run both FE and BE together using Docker Compose.
- Prerequisites:
- Docker installed: https://docs.docker.com/get-docker/
- Docker Compose installed: https://docs.docker.com/compose/install/

1. **Clone this repository**:

````bash
git clone https://github.com/sharifmrahat/localama.git
cd localama
```

2. **Run docker compose**:
```bash
docker-compose up -d
````

3. **Stop the services**:

```bash
docker-compose down
```

4. **Check the status**

```bash
docker ps
```

## 🛠 Tech Stack

- Frontend: SvelteKit, Bun, TailwindCSS, Shadcn
- Backend: NestJS, Node.js, Ollama, SSE
- Tools: Docker & Docker Compose

## ✨ Features

- 🚀 AI-powered processing

- 🖥 Modern and responsive UI

- 🔗 Seamless FE & BE integration

- 🐳 Docker support

- 📦 Bun-powered fast builds

<!-- ## 📈 Areas of Enhancement


Improve real-time data streaming

Optimize database queries

Enhance UI/UX with animations

Add unit and integration tests -->

## 🤝 Contribution

- Fork the repository
- Create a feature branch (git checkout -b feature-name)
- Commit changes (git commit -m 'Add feature')
- Push and open a PR
