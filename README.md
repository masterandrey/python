[![Docker Automated build](https://img.shields.io/docker/image-size/andgineer/fastapi)](https://hub.docker.com/r/andgineer/fastapi)

## About

Python FastAPI [Docker Container](https://hub.docker.com/r/andgineer/fastapi) with MongoDB support on lightweight Alpine Linux.

- FastAPI
- Mongo DB
- OpenSSL

As an extremely fast Python package manager, the container uses  
[Astral's uv](https://github.com/astral-sh/uv).

## Usage

    docker run -it --rm -v $PWD/example:/app:ro andgineer/fastapi app/ping.py
