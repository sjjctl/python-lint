FROM python:3.10.4-alpine3.15

LABEL maintainer="sjjctl@protonmail.com"

RUN apk add --no-cache \
    gcc \
    musl-dev && \
    pip install pylint==2.7.4 \
    pylint_django==2.4.3 \
    pycodestyle==2.7.0 \
    flake8==3.9.1 \
    black==20.8b1 \
    mypy==0.812 \
    isort==5.8.0
