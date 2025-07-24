

# 🧱 NextJS-Jenkins-Docker

[![Build](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/your-username/NextJS-Jenkins-Docker)
[![Dockerized](https://img.shields.io/badge/docker-ready-blue)](https://hub.docker.com/)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

A CI/CD-ready boilerplate integrating **Next.js**, **Docker**, and **Jenkins** for building, testing, and deploying modern web applications with ease. Ideal for solo projects, teams, or DevOps experimentation.

---

## 🧰 Tech Stack

| Technology  | Description                           |
|-------------|---------------------------------------|
| **Next.js** | React framework with SSR/SSG support  |
| **Docker**  | Containerizes the app for any platform|
| **Jenkins** | Automates CI/CD workflow              |

---

## 🚀 Features

- 🔧 Optimized `Dockerfile` for Next.js production builds
- ⚙️ Jenkins pipeline for automated build, test, and deploy workflows
- 🌍 Multi-environment configuration support
- 🔁 Seamless integration with cloud providers (AWS, GCP, etc.)
- 🧪 Extendable with testing, linting, and caching

---

## 📁 Folder Structure

```text
NextJS-Jenkins-Docker/
├── .github/              # GitHub Actions workflows (optional)
├── .dockerignore         # Excludes unnecessary files from Docker context
├── Dockerfile            # Docker instructions for building the app
├── Jenkinsfile           # Jenkins CI/CD pipeline configuration
├── next.config.js        # Next.js configuration
├── package.json          # Project dependencies and scripts
├── app/                  # Next.js App Router directory
├── public/               # Static assets
├── styles/               # CSS/SCSS/Tailwind styles
└── README.md             # Project documentation (this file)
```

---

## 🔰 Get Started

Follow these steps to clone, install, and run the app:

### 🧾 Clone the Repository

```bash
git clone https://github.com/samuellachisa/NextJS-Jenkins-Docker.git
cd NextJS-Jenkins-Docker
```

### 🧪 Local Development

#### Prerequisites

- Node.js (v18 or higher)
- Docker
- npm or Yarn

#### Run Next.js Locally (No Docker)

```bash
npm install
npm run dev
```

#### Build and Run with Docker

```bash
# Build the Docker image
docker build -t nextjs-app .

# Run the container
docker run -p 3000:3000 nextjs-app
```

