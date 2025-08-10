🏋️‍♂️ Fitness App Microservices

A full-stack fitness application built with Spring Boot microservices 💻 and a Vite + React frontend ⚡.
Features secure authentication 🔐 with Keycloak, service discovery 🔍 via Eureka, and centralized configuration ⚙️ with Spring Cloud Config — all fully containerized 🐳 using Docker & Docker Compose.

⸻

🏗️ Architecture Overview
<img width="3636" height="3347" alt="Microservices" src="https://github.com/user-attachments/assets/83adddd3-fed6-4ad1-a140-3e736dfe6892" />





🔹 Backend Microservices
	•	userservice 👤 – Manages user profiles & accounts
	•	activityservice 🏃 – Tracks workouts & activities
	•	aiservice 🤖 – AI-powered recommendations
	•	gateway 🚪 – API gateway & routing
	•	configserver ⚙️ – Centralized configuration
	•	eureka 📡 – Service discovery

🔹 Configuration & Service Discovery
	•	Spring Cloud Config – Centralized configs for all services
	•	Eureka Server – Dynamic service registration & discovery

🔹 Authentication
	•	Keycloak – OAuth2 & OpenID Connect based auth

🔹 Frontend
	•	Vite + React – Modern, fast UI ⚡
	•	Served via Nginx in a container

🔹 Messaging & Persistence
	•	PostgreSQL 🐘 – Relational data storage
	•	MongoDB 🍃 – NoSQL document database
	•	RabbitMQ 🐇 – Message broker for async communication

⸻

✨ Features

✅ Fully containerized stack
✅ Dynamic, centralized configuration
✅ Secure role-based authentication
✅ Real-time service discovery
✅ Modern, responsive frontend
✅ Works locally with Docker Compose

