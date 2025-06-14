# 🕒 Go DateTime App

A simple GoLang web application that displays the **current date and time**, containerized using **Docker** and deployed using **Kubernetes**.

---

## 📌 Features

- Built using GoLang's `net/http` package
- Containerized with Docker
- Kubernetes deployment with 2 replicas
- Exposed to the internet via LoadBalancer service

---

## 🗂️ Project Structure

go-datetime-app/
├── main.go # Go web server
├── Dockerfile # Docker build file
├── deployment.yaml # Kubernetes Deployment (2 replicas)
└── service.yaml # Kubernetes LoadBalancer Service
