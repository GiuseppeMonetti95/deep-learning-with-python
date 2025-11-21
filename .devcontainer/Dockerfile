FROM mcr.microsoft.com/devcontainers/python:2-3.12-bullseye

SHELL [ "/bin/bash" , "-c" ]

# Install essential packages
RUN apt update && apt install -y \
    --no-install-recommends \
    ca-certificates gpg wget git curl zip

# Install nbconvert for git pre-commit hooks
RUN pip3 install --no-cache-dir nbconvert
