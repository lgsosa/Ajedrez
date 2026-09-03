# Chess in Python ♟️

University software project developed in **Python**, focused on object-oriented design, testing, containerization and continuous integration.

## Highlights

- Python application implementing chess logic and piece movement rules
- **Dockerized** execution environment
- Automated tests and coverage configuration
- **CircleCI** continuous integration pipeline
- Code quality monitoring with **Code Climate**
- Git/GitHub workflow used throughout development

## Tech stack

`Python` · `Docker` · `CircleCI` · `Git` · `GitHub` · `Testing` · `Code Climate`

## Run locally

### Requirements

- Docker
- Python 3.x

### Clone the repository

```bash
git clone https://github.com/lgsosa/Ajedrez.git
cd Ajedrez
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Build the Docker image

```bash
docker build -t chess-python .
```

### Run the container

```bash
docker run -i chess-python
```

## CI/CD and quality

This project includes configuration for automated validation through **CircleCI**, alongside maintainability and test coverage tooling. It was developed as part of my Computer Engineering studies and gave me hands-on experience with containerized applications and CI workflows.

## What I practiced

- Structuring a Python project
- Writing and running automated tests
- Packaging an application with Docker
- Working with a CI pipeline
- Tracking maintainability and test coverage
- Using Git in an academic software project
