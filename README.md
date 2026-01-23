# Pywikibot Docker Image

[![Build](https://github.com/jmnote/docker-pywikibot/actions/workflows/build.yml/badge.svg)](https://github.com/jmnote/docker-pywikibot/actions/workflows/build.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/jmnote/pywikibot)](https://hub.docker.com/r/jmnote/pywikibot)
[![GitHub Container Registry](https://img.shields.io/badge/GHCR-jmnote%2Fpywikibot-blue)](https://github.com/jmnote/docker-pywikibot/pkgs/container/pywikibot)

This repository provides the Docker build configuration for [Pywikibot](https://www.mediawiki.org/wiki/Manual:Pywikibot), automatically tracking upstream tags from [wikimedia/pywikibot](https://github.com/wikimedia/pywikibot).

The build workflow checks for new semantic version tags (e.g., `X.Y.Z`) and pushes multi-architecture images to both **Docker Hub** and **GitHub Container Registry (GHCR)**.

## Features

- **Multi-Architecture:** Supports `linux/amd64` and `linux/arm64`.
- **Automated Builds:** Syncs with upstream releases automatically.
- **Semantic Versioning:** Provides `latest`, major (`X`), minor (`X.Y`), and patch (`X.Y.Z`) tags.

## Image Registries

You can pull the image from either registry:

### Docker Hub
```bash
docker pull jmnote/pywikibot:latest
```

### GitHub Container Registry
```bash
docker pull ghcr.io/jmnote/pywikibot:latest
```
