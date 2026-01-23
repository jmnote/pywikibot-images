# Unofficial Pywikibot Docker Image

[![Build](https://github.com/jmnote/pywikibot/actions/workflows/build.yml/badge.svg)](https://github.com/jmnote/pywikibot/actions/workflows/build.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/jmnote/pywikibot)](https://hub.docker.com/r/jmnote/pywikibot)
[![GitHub Container Registry](https://img.shields.io/badge/GHCR-jmnote%2Fpywikibot-blue)](https://github.com/jmnote/pywikibot/pkgs/container/pywikibot)

This repository automatically builds and pushes multi-architecture Docker images for [Pywikibot](https://www.mediawiki.org/wiki/Manual:Pywikibot) based on the upstream tags from [wikimedia/pywikibot](https://github.com/wikimedia/pywikibot).

The build workflow runs daily to check for new semantic version tags (e.g., `X.Y.Z`) and pushes images to both **Docker Hub** and **GitHub Container Registry (GHCR)**.

## Supported Architectures

- `linux/amd64`
- `linux/arm64`

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
