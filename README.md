# 🧱 NextJS-Jenkins-Docker

[![Build](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/your-username/NextJS-Jenkins-Docker)
[![Dockerized](https://img.shields.io/badge/docker-ready-blue)](https://hub.docker.com/)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

A CI/CD-ready boilerplate that integrates **Next.js**, **Docker**, and **Jenkins** for building, testing, and deploying modern web applications with ease. Ideal for solo projects, teams, or DevOps experimentation.

---

## 🧰 Tech Stack

| Tech        | Description                           |
|-------------|---------------------------------------|
| **Next.js** | React framework with SSR/SSG support  |
| **Docker**  | Containerizes the app for any platform|
| **Jenkins** | Automates CI/CD workflow              |

---

## 🚀 Features

- 🔧 Dockerfile optimized for Next.js production builds
- ⚙️ Jenkins pipeline to build, test, and deploy your app
- 🌍 Multi-environment configuration support
- 🔁 Easy cloud provider integration (AWS, GCP, etc.)
- 🧪 Extendable with testing, linting, and caching

---

### 📁 Folder Structure

```text
NextJS-Jenkins-Docker/
├── .github/              # GitHub workflows (optional)
├── .dockerignore         # Excludes junk from Docker context
├── Dockerfile            # Docker instructions
├── Jenkinsfile           # CI/CD pipeline for Jenkins
├── next.config.js        # Next.js config
├── package.json          # Dependencies
├── app/                  # Next.js App Directory
├── public/               # Static assets
├── styles/               # CSS/SCSS/Tailwind
└── README.md             # You’re looking at it 👀
```


## 🔰 Get Started

Follow these steps to clone, install, and run the app:

### 🧾 Clone the Repository

```bash
git clone https://github.com/samuellachisa/NextJS-Jenkin-Docker.git
cd NextJS-Jenkin-Docker

---



### 🧪 Local Development

### Prerequisites

- Node.js (v18+)
- Docker
- npm or yarn

### Run Next.js locally (no Docker)

```bash
npm install
npm run dev

# Build the Docker image
docker build -t nextjs-app .

# Run the container
docker run -p 3000:3000 nextjs-app

