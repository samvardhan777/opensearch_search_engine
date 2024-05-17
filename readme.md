# OpenSearch Docker Setup

This repository provides Docker Compose files for easily running OpenSearch and OpenSearch Dashboards. It's designed to help users quickly set up a local search and visualization environment for managing and exploring data.

## Prerequisites

Before setting up, ensure you have the following installed on your system:

- **Docker**: You can install Docker by following the instructions here: [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: You can install Docker Compose by following the instructions here: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/opensearch-docker-setup.git
```

## Running OpenSearch

To start OpenSearch and OpenSearch Dashboards, execute the following command:

```bash
docker-compose up -d
```

## Accessing OpenSearch Dashboards

Once the services are running, OpenSearch Dashboards can be accessed at:

[http://localhost:5601/app/home#/](http://localhost:5601/app/home#/)

Here you can create and manage your visualizations, dashboards, and explore your data.


# Stopping OpenSearch

```
docker-compose down
```

