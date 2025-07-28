## Deploying Web App with Nginx and MySQL using Docker Compose

> **Note:** The source code of the web application used in this project is **not developed by me**. My contribution is focused entirely on writing the `Dockerfile` and `docker-compose.yml` to containerize and deploy the application locally.

### 🛠 Project Description

This project demonstrates how to deploy a web application using **Docker Compose**, with the following setup:

- **Nginx** as a reverse proxy
    
- **MySQL** as the database service
    
- **Docker** and **Docker Compose** for container
    

The goal is to provide a simple, reproducible environment to run the app locally using containers.

### 📦 Features

- Containerized web app deployment
    
- Nginx setup as a reverse proxy
    
- Persistent MySQL database using Docker volumes
    
- Simple and modular `docker-compose.yml` for local development
    

### 🚀 Getting Started

Clone the repository and run:

```bash
docker compose up --build
```

### 📁 Project Structure

```
.
├── Dockerfile
├── docker-compose.yml
├── nginx/
│   └── default.conf
├── webapp/  # cloned or downloaded web application source code
└── README.md
```

### 📌 Requirements

- Docker
    
- Docker Compose


### Clone Repo
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```
