# Prestashop Docker Compose

Docker compose configuration for Prestashop development. Comes bundled with a phpMyAdmin instance for db inspect and debug.

## Requirements

- Docker 1.10.0+

## Setup

Clone or download the repo

## Running

```bash
docker-compose up
```

Or in detached mode:

```bash
docker-compose up -d
```

Go to http://localhost:8090 to see the site. Admin is on http://localhost:8090/adminTest. Credentials: *user*: `dev@qvo.cl`, *password*: `12345678`

Prestashop files are in `prestashop_data/`

> If it's the first time running it, wait a moment to let Prestashop installation to finish.

phpMyAdmin is on http://localhost:8091. Credentials: *user*: `root`, *password*: `password`
