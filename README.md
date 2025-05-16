# BlazeChat Backend Infrastructure

This repository contains the docker files to run the services
we need for blazechat such as a redis database for caching and another
for job queues.

## Prerequisites

1. Docker CLI
1. Docker Engine
1. Valid environment file

## Running

Run:
```bash
$ docker compose up -d
```

## Stopping

Run:
```bash
$ docker compose down
```
