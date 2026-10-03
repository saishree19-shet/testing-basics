
# Jenkins + Docker CI/CD Pipeline

This project demonstrates a basic **CI/CD pipeline using GitHub, Jenkins, Docker, and ngrok**.

Whenever changes are pushed to the GitHub repository, a GitHub webhook triggers Jenkins. Jenkins then pulls the latest code, builds a Docker image, removes the previous container, and deploys a new container automatically.

---

## 🚀 Technologies Used

- **Git & GitHub** – Source code management
- **Jenkins** – CI/CD automation
- **Docker** – Containerization and deployment
- **Node.js** – Application runtime
- **ngrok** – Exposes the local Jenkins server for GitHub webhooks

---

## 📁 Project Structure

```text
jenkins-testing/
│
├── docker/
│   ├── Dockerfile
│   ├── app.js
│   ├── package.json
│   └── package-lock.json
│
└── README.md
