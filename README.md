[![Docker Automated build](https://img.shields.io/docker/image-size/andgineer/python)](https://hub.docker.com/r/andgineer/python)

## About

Alpine-based opionated [docker image](https://hub.docker.com/r/andgineer/python) for Python with FastAPI in less than 300MB.

As an extremely fast Python package manager, the container uses  
[Astral's uv](https://github.com/astral-sh/uv).

- FastAPI
- Mongo DB
- OpenSSL
- UV

## Usage

    docker run -it --rm -v $PWD/example:/app:ro andgineer/python app/ping.py
