# IBM Hacktiv8 Lab

Docker Compose setup for running Langflow.

## Services

- **Langflow** — visual workflow builder for AI apps (port 7860)

## Prerequisites

- Docker and Docker Compose

## Setup

1. Copy `.env.example` to `.env`:

   ```sh
   cp .env.example .env
   ```

2. Start the services:

   ```sh
   docker compose up -d
   ```

3. Open Langflow at http://localhost:7860.

## Stopping

```sh
docker compose down
```

To remove volumes as well:

```sh
docker compose down -v
```
