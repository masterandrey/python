[![Docker Automated build](https://img.shields.io/docker/image-size/andgineer/python)](https://hub.docker.com/r/andgineer/python)

## About

Alpine-based opionated [docker image](https://hub.docker.com/r/andgineer/python) for Python with FastAPI in less than 300MB.

- FastAPI
- Mongo DB
- OpenSSL
- UV

As an extremely fast Python package manager, the container uses  
[Astral's uv](https://github.com/astral-sh/uv).


## Usage

    docker run -it --rm -v $PWD/example:/app:ro andgineer/python app/ping.py
