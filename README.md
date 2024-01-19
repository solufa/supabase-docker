# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.

## Setup

```sh
$ cp .env.example .env
$ docker compose -f docker-compose.yml -f dev/docker-compose.dev.yml up -d
```

#### GUI

Studio: http://localhost:8000  
Inbucket: http://localhost:9000
