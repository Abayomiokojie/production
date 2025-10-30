FROM python:3.11-slim-buster

# FROM python:3.11-slim-bookworm

# Update OS packages to fix vulnerabilities
# RUN apt-get update && apt-get upgrade -y && apt-get clean

# Install python package
COPY requirements.txt /tmp/
RUN pip install --no-cache-dir -r /tmp/requirements.txt

