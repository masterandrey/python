[![Docker Automated build](https://img.shields.io/docker/image-size/andgineer/python)](https://hub.docker.com/r/andgineer/python)

## About

Alpine-based opionated [docker image](https://hub.docker.com/r/andgineer/python) for Python with fastapi, Mongo and Openssl in less than 300M

## Usage

    docker run -it --rm -v $PWD/example:/app:ro andgineer/python app/ping.py
