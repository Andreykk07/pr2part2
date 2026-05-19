# pr2part2

# Multi-Service Chat Application

## Services
- **Nginx**: Reverse proxy with WebSocket and sticky sessions (`ip_hash`) support.
- **API**: Node.js REST & WebSocket server (scaled to 2 replicas in production).
- **PostgreSQL**: Relational database for persistence.
- **Redis**: In-memory data store for Pub/Sub and session management.

## Prerequisites
- Docker (v20.10+)
- Docker Compose (v2.20+)

## Environment Setup
```bash
cp .env.example .env
