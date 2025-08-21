# Flask Monolith to Microservice PoC

This repository is a **Proof of Concept (PoC)** for converting a monolithic Flask + PostgreSQL application into a **microservice-ready architecture**.

This project uses:

- Flask backend with **Jinja2 templates** for frontend rendering.
- PostgreSQL as a **StatefulSet** on Kubernetes.
- Dockerized setup for easy local development and Kubernetes deployment.

---

## Features

- **User Management**: Register and list users with credentials.
- **Frontend**: Jinja2 templates served by Flask.
- **Backend**: REST API built with Flask and SQLAlchemy.
- **Database**: PostgreSQL running as a StatefulSet in Kubernetes.
- **Single Container Deployment**: Frontend and backend run in one server for simplicity.
- **Deployment Ready**: Docker images and Kubernetes manifests included.

---

## Architecture

