FROM ubuntu:20.04

LABEL maintainer="ilya.evseev@gmail.com" \
      version="2020.12.30.0511" \
      description="Docker image for using in .gitlab-ci.yml at deploy stage"

RUN apt update && \
    apt install ansible -y --no-install-recommends && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*
