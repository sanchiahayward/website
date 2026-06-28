# Sanchia Hair Website Docker Preview

Static preview site for Sanchia Hair.

## Run with Docker

```bash
cd /home/hermes/sanchia-website-container
docker compose up -d --build
```

Open: http://localhost:8088

## Stop

```bash
docker compose down
```

## Contents

- `site/index.html` — website copy/layout
- `site/styles.css` — linen/sage/olive/black styling
- `site/assets/sanchia-logo-black.png` — real Sanchia Hair logo asset
- `Dockerfile` — nginx static server container
- `docker-compose.yml` — maps local port 8088 to container port 80

Note: this machine currently does not have Docker installed, so the files are ready to run on a Docker-enabled machine, but I cannot build the image here until Docker is installed.
