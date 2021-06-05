FROM node:8.16.0-alpine

LABEL maintainer="ilya.evseev@gmail.com" \
      version="2021.01.10.0130" \
      description="Docker image for using in .gitlab-ci.yml at deploy stage"

WORKDIR /home

CMD "npm install && npm run build"
