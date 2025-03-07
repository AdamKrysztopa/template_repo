# Use the official Python image as a base
ARG VARIANT="3.11"
FROM python:${VARIANT}

# Install uv
RUN curl -LsSf https://astral.sh/uv/install.sh | sh

# Install other tools
RUN pip install pyright ruff black uvicorn

# Set the default shell to bash
SHELL ["/bin/bash", "-c"]