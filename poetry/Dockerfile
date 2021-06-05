FROM  tiangolo/uvicorn-gunicorn-fastapi:python3.8

LABEL maintainer="ilya.evseev@gmail.com" \
      location="evseev/poetry"           \
      version="2021.06.05.0909"          \
      description="Docker image for using in .gitlab-ci.yml at deploy stage"

RUN   curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | POETRY_HOME=/opt/poetry python && \
      cd /usr/local/bin               && \
      ln -s /opt/poetry/bin/poetry    && \
      poetry config virtualenvs.create false
