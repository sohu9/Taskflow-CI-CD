# 🚀 TaskFlow CI/CD

A Node.js Task Management application with a complete CI/CD pipeline using GitHub Webhooks, Jenkins, Docker, and AWS EC2.

---

## 📌 Features

- ✅ Create Tasks
- ✅ Edit Tasks
- ✅ Delete Tasks
- ✅ Responsive User Interface
- ✅ Dockerized Application
- ✅ Automated CI/CD Pipeline
- ✅ Automatic Deployment on Code Push

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- EJS
- Git & GitHub
- GitHub Webhooks
- Jenkins
- Docker
- AWS EC2

---

## 🔄 CI/CD Workflow

```text
Developer
     │
     ▼
Git Push
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Webhook
     │
     ▼
Jenkins
     │
     ▼
Build Docker Image
     │
     ▼
Stop Existing Container
     │
     ▼
Deploy New Container
     │
     ▼
AWS EC2
     │
     ▼
Live Application
```

---

## 📥 Installation

### Clone Repository

```bash
git clone https://github.com/sohu9/Taskflow-CI-CD.git
cd Taskflow-CI-CD
```

### Install Dependencies

```bash
npm install
```

### Run the Application

```bash
node app.js
```

Open your browser and visit:

```
http://localhost:8000
```

---

## 🐳 Run with Docker

### Build Docker Image

```bash
docker build -t node-taskflow-app .
```

### Run Docker Container

```bash
docker run -d -p 8000:8000 --name taskflow-container node-taskflow-app
```

Visit:

```
http://localhost:8000
```

---

## ⚙️ CI/CD Pipeline

Whenever code is pushed to the **main** branch:

1. GitHub Webhook automatically triggers Jenkins.
2. Jenkins pulls the latest source code.
3. Jenkins builds a new Docker image.
4. The existing Docker container is stopped and removed.
5. A new container is deployed automatically on AWS EC2.
6. The latest application changes become live without manual deployment.

---

## 🎯 Project Highlights

- End-to-End CI/CD Pipeline
- Automated Deployment
- Docker Containerization
- GitHub Webhook Integration
- Jenkins Automation
- AWS EC2 Deployment
- Zero Manual Deployment After Git Push

---

## 👨‍💻 Author

**Momin Shoaib Akhter**

GitHub: https://github.com/sohu9

---

⭐ If you like this project, don't forget to give it a Star!
