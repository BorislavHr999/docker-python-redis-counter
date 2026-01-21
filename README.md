# 🐍 Docker Python + Redis Counter

This project demonstrates **container networking** and **custom image building**.

🔹 **Goal:** Connect a Flask Web App to a Redis Cache Service. 🔗
🔹 **Architecture:**
  - **App:** Python Flask (Builds from `Dockerfile`)
  - **Database:** Redis (Official Image)
🔹 **Key Learning:** Instead of IP addresses, the app connects using the hostname `redis`, resolved automatically by Docker's internal DNS. 🧠

---
**How to run:**
```bash
docker-compose up -d --build
