# Advanced Static Website with Docker, Nginx, and CI/CD 🚀

This repository contains a **Dockerized static website** that utilizes **Nginx for advanced configurations**, serving **HTML, CSS, and JavaScript** files efficiently. Additionally, it integrates **GitHub Actions for CI/CD**, enabling automated builds and deployments to Docker Hub or other environments.

## 📦 Features
- **Full Static Website:** HTML, CSS, and JavaScript served by Nginx.
- **Advanced Nginx Configuration:** Custom `default.conf` for optimized performance.
- **Docker Compose Setup:** Easily manage services and volumes.
- **CI/CD with GitHub Actions:** Automates build and push to Docker Hub.
- **Portability & Scalability:** Deploys anywhere with minimal configuration.

## 🔧 Tech Stack
- **HTML** - Markup structure for the web pages.
- **CSS** - Styling for the website.
- **JavaScript** – Adds interactivity.
- **Nginx** – Serves static files with advanced configurations.
- **Docker** – Containerizes the application for portability.
- **Docker Compose** – Manages multi-container setup.
- **GitHub Actions** – Automates Docker builds and pushes to Docker Hub.
- **Docker Hub** – Stores and distributes Docker images.

## 🚀 Getting Started

### 🐳 Docker Image

This application is available on **Docker Hub**:

[![Docker Pulls](https://img.shields.io/docker/pulls/caiobom/docker-website-nginx-html-advanced?style=flat-square)](https://hub.docker.com/r/caiobom/docker-website-nginx-html-advanced)

### 📥 **Cloning the Repository**
To get started, first **clone the repository**:

```sh
git clone https://github.com/caaiobomfim/docker-website-nginx-html-advanced.git
```

### 🔥 Running the Application with Docker Compose
Run the following command to build and start the containers:

```sh
cd docker-website-nginx-html-advanced
docker-compose up -d --build
```

### 🌍 Testing the Application
Once the containers are running, access:

```sh
http://localhost:8080
```

Or use curl:

```sh
curl http://localhost:8080
```