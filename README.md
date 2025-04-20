# CI/CD Pipeline with GitHub Actions

This project demonstrates a simple CI/CD pipeline using GitHub Actions for a basic Flask web app.

## Tech Stack
- GitHub Actions
- Python / Flask
- CI: Linting, Testing
- CD: Simulated deploy

## Setup
1. Clone the repo
2. Navigate to `ci-cd-pipeline/app`
3. Run `pip install -r requirements.txt`
4. Start the app with `python app.py`

## Workflow
Triggers on push to `main`. It installs dependencies, runs a mock test, and simulates deployment.
