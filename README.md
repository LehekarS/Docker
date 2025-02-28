🐳 Docker Practicals Repository
This repository contains various hands-on Docker practicals, including:

Docker Compose 3-Tier Project
Multi-Stage Builds for Different Applications
Dockerfiles for Various Use Cases
🛠️ Understanding Docker Terminologies
🏗️ Dockerfile
A script that contains instructions to build a Docker image. Think of it as a recipe for creating a container.

📦 Docker Image
A snapshot of an application and its dependencies. Containers are created from images.

🚢 Docker Container
A running instance of a Docker image. Containers are lightweight and isolated from each other.

🔄 Docker Compose
A tool for defining and running multi-container applications using a YAML file.

🎭 Multi-Stage Build
A way to optimize Docker images by using multiple build steps, reducing the final image size.

📂 Repository Content
📌 1. Docker Compose 3-Tier Project
This directory contains a three-tier architecture project using Docker Compose, including:

web (nginx)
Backend (Node.js)
Database (mongodb)


📌 2. Multi-Stage Build for Various Applications
This section contains optimized multi-stage Dockerfiles for different applications like Node.js, Python, and Java. Multi-stage builds help reduce the final image size and improve security.


📌 3. Dockerfiles for Various Applications
This directory has individual Dockerfiles for different applications, demonstrating how to containerize them properly.


🚀 Getting Started
1️⃣ Clone the repository:
git clone https://github.com/user/repo.git

2️⃣ Navigate to a project directory:
cd docker-compose-3-tier

3️⃣ Run Docker Compose:
docker-compose up -d
