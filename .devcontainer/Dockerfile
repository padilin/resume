FROM mcr.microsoft.com/devcontainers/python:0-3.11-bullseye

RUN apt-get update && apt-get install -y texlive-full

RUN pip install --no-cache-dir --update pip wheel
RUN pip install --no-cache-dir rendercv[full]
