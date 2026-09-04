# Development Containers (Ansible)

[![Container Release (devcontainer-ansible)](https://github.com/leberkaslabs/devcontainer-image-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/leberkaslabs/devcontainer-image-ansible/actions/workflows/build.yml)

This repository provides a Docker image for Ansible in a [Development Containers](https://containers.dev/).

```bash
docker pull dudecalledbro/devcontainer-ansible:latest
```

## Build

This image build is scheduled with GitHub Actions and will be pushed to DockerHub. The image will also be rebuilt, if the `main` branch is updated. If you need to build the image locally, ensure [Docker](https://docs.docker.com/engine/installation/) is installed and execute the following:

```bash
docker build -t devcontainer-ansible:latest .
```

## License

Copyright (c) 2026 Niclas Spreng
