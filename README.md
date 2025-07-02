  # Microservices Docker Project 🚀

This project demonstrates a simple microservices architecture using **Node.js**, **Express**, and **Docker**, orchestrated with **Docker Compose**. It consists of independent services communicating via REST APIs, along with a frontend to consume those services.

---

## 🏗️ **Project Structure**

microservices-docker-project/
├── docker-compose.yml # Docker Compose setup
├── user-service/ # Handles user-related operations
├── product-service/ # Handles product-related operations
└── frontend/ # Simple Nginx-based frontend

---

## 🧩 **Microservices**

| Service         | Tech Stack | Description                         | Port  |
|-----------------|------------|-------------------------------------|-------|
| **user-service**    | Node.js, Express | Provides user data via REST API      | 5000  |
| **product-service** | Node.js, Express | Provides product data via REST API   | 5001  |
| **frontend**        | Nginx, HTML/JS   | Simple static frontend to consume APIs | 8080 |

---

## ⚒️ **How to Run**

Make sure **Docker** and **Docker Compose** are installed.

### Step 1: Clone the Repository

```bash
git clone git@github.com:ayyagari-dev/microservices-docker-project.git
cd microservices-docker-project
docker-compose up --build
