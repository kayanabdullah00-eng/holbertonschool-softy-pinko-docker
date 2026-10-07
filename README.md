# Holberton School - Softy Pinko Docker

This repository contains Docker-related tasks for the Holberton School project.

## Task 0 - Create Your First Docker Image

In this task, a Docker image is created using Ubuntu as the base image.

The Dockerfile:

- Uses the latest Ubuntu image
- Updates APT packages
- Upgrades installed packages
- Prints `Hello, World!` when the container runs

### Build the Docker Image

```bash
docker build -f ./Dockerfile -t softy-pinko:task0 .
```

### Run the Container

```bash
docker run -it --rm --name softy-pinko-task0 softy-pinko:task0
```

Expected output:

```text
Hello, World!
```

## Repository Structure

```text
holbertonschool-softy-pinko-docker/
└── task0/
    └── Dockerfile
```
