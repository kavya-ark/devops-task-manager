# DevOps Task Manager Application

 Overview
A simple task management application built to demonstrate DevOps practices such as version control, CI/CD, and containerized deployment.

GitHub Repo: https://github.com/kavya-ark/devops-task-manager

---

 Tech Stack
- Git & GitHub
- Docker
- Jenkins (CI/CD)
- Linux
- Python (or Web Framework if applicable)

---

 Features
- Create, read, update, delete tasks
- Simple web-based or API-based structure
- Dockerized application
- CI/CD ready setup

---

Workflow
Developer → GitHub → Jenkins → Docker Build → Deployment

---

Setup Instructions

```bash
git clone git@github.com:kavya-ark/devops-task-manager.git
cd devops-task-manager
docker build -t task-manager .
docker run -p 5000:5000 task-manager
