FROM  python:3.9-alpine3.13
LABEL maintainer = "Shyned"

ENV PYTHONUNBUFFERED 1

COPY ./requirments.txt /tmp/requirments.txt
COPY ./app /app
WORKDIR /app
EXPOSE 8000
