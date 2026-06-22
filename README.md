# SearXNG

Self-hosted SearXNG search backend used for personal projects and future web applications.

## What is this?

This repository contains the Docker setup for running a private SearXNG instance.

It provides a unified search API that aggregates results from multiple search engines and can be used as the search layer for applications such as:

* Internship finder
* Client discovery platform
* AI SDR systems
* OSINT and research tools

## Features

* Self-hosted
* Docker-based deployment
* Production-ready compose file
* Easily deployable to a VPS or home server
* Can be exposed through Traefik and HTTPS
* Provides JSON API access for Python applications

## Quick Start

```bash
docker compose up -d
```

Open:

```
http://localhost:8080
```

Example API request:

```bash
curl "http://localhost:8080/search?q=backend+engineer&format=json"
```

## Purpose

This repository serves as the search infrastructure layer for future projects that require reliable and programmable web search capabilities.
