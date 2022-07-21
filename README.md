# MKC Trading terminal

This is docker-compose file and directory structure guideline for deploy UAT, Prod.

For production, please add logging driver to keep logs from all system.

# Running Prerequisite

## Cloning this repo

```bash
git clone https://github.com/Shayennn/Merkle-Docker.git
```

## How to run

```bash
gcloud auth activate-service-account sa-foobar@sa-foobar.iam.gserviceaccount.com --key-file=service-account.json
gcloud auth configure-docker asia-southeast1-docker.pkg.de
docker-compose up
```
