# Proyecto Despliegue ADSO

API REST desarrollada en Flask, containerizada con Docker y desplegada en un servidor AWS EC2 con HTTPS mediante Nginx Proxy Manager y Let's Encrypt.

## 🚀 Demo en producción

🔗 https://harol-adso-proyecto.duckdns.org

## 📦 Endpoints

- `GET /` – Endpoint principal
- `GET /health` – Verifica el estado del servicio
- `GET /db-check` – Verifica la conexión a la base de datos MySQL

## 🐳 Imagen en Docker Hub

🔗 https://hub.docker.com/r/harolimpos/proyecto-api

## 🏗️ Stack tecnológico

- **Backend:** Python + Flask
- **Base de datos:** MySQL
- **Proxy / SSL:** Nginx Proxy Manager + Let's Encrypt
- **Contenedores:** Docker + Docker Compose
- **Infraestructura:** AWS EC2
- **Dominio:** DuckDNS

## ⚙️ Despliegue

```bash
docker compose up -d --build
```

Levanta 3 contenedores: la API, MySQL y Nginx Proxy Manager.

## 👤 Autor

Harold – Proyecto ADSO
