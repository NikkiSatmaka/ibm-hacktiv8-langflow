# IBM Hacktiv8 Lab

Docker Compose setup for running Langflow with ChromaDB and OpenAI.

## Services

- **Langflow** — visual workflow builder for AI apps (port 7860)
- **ChromaDB** — vector database for embeddings

## Prerequisites

- Docker and Docker Compose
- An OpenAI API key (or compatible provider)

## Setup

1. Copy `.env.example` to `.env` and fill in your API credentials:

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
