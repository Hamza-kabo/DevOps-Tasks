# DevOps Tasks

Hands-on DevOps tasks completed during my industrial training (SIWES) internship: containerizing a Flask web application with Docker, orchestrating it with Docker Compose, and automating workflows with GitHub Actions.

## Repo Structure

### Root: Flask app in Docker

- `main.py`: a small Flask application that serves `index.html`. The port is set by the `PORT` environment variable (default `8080`).
- `index.html`: the page served by the app.
- `Dockerfile`: builds a container image for the app (Python base image, installs Flask, runs `main.py`).
- `.github/workflows/`: GitHub Actions workflow for this repository.

### `L4-containerization/`

- `Dockerfile`: container image definition.
- Docker Compose file: defines and runs the containerized service.
- HTML file: the page served by the container.

### `flask_task/`

- `.github/workflows/`: a GitHub Actions workflow file for a Flask task.

## Tools

- **Containers:** Docker, Docker Compose
- **CI/CD:** GitHub Actions
- **Application:** Python (Flask), HTML
- **Version control:** Git, GitHub

## Purpose

This repository documents practical DevOps skills, including:

- Packaging a web application into a Docker image
- Running multi-container setups with Docker Compose
- Automating build and test steps with GitHub Actions

## Author

Hamza Adam Aliyu: [LinkedIn](https://linkedin.com/in/hamza-adam-aliyu)
