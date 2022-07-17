# MKC Trading terminal

This is docker-compose file and directory structure guideline for deploy UAT.

For production, please add logging driver to keep logs from all system.

# Running Prerequisite

## Cloning this repo

```bash
git clone --recurse-submodules -j8 https://github.com/Shayennn/Merkle-Docker.git
```

## .env file

1. Copy .env.example to .env and edit the file.
2. Copy .env file into frontend before build to let it build with correctly path and URL.

## Docker Image

```bash
docker-compose --build up
```
