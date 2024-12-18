# DTWithDockerCompose

This repository contains the `docker-compose.yml` file required to run the **Dynatrace OneAgent** alongside an ASP.NET Core Minimal API. The OneAgent will monitor the API's activity.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- Docker
- Docker Compose

### Setting Up the Environment

Before running the `docker-compose` file, create the necessary directories for mounts by running the following commands in the directory containing `docker-compose.yml`:

```bash
mkdir -p dynatrace/oneagent
mkdir -p dynatrace/log
mkdir -p dynatrace/lib/oneagent
mkdir -p dynatrace/lib/enrichment
