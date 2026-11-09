# Multi-container Fibonacci example

A React UI, Express API and background worker using PostgreSQL and Redis, routed through Nginx.

For the local example, run `docker compose -f docker-compose-dev.yml up --build` and open `http://localhost:3050`. The development file includes disposable local database credentials; do not use them for a deployed service.

The separate `docker-compose.yml` uses prebuilt images and externally configured database services.
