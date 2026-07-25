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

2. Edit `.env` and set variables for:

   ```sh
   LANGFLOW_AUTO_LOGIN
   LANGFLOW_SUPERUSER
   LANGFLOW_SUPERUSER_PASSWORD
   ```

3. Start the services:

   ```sh
   docker compose up -d
   ```

4. Open Langflow at <http://localhost:7860>.

## Stopping

```sh
docker compose down
```

To remove volumes as well:

```sh
docker compose down -v
```
