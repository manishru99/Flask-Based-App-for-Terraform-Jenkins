# Flask-Based-App-for-Terraform-Jenkins

This repository contains a simple **Flask web application** designed to be deployed using Terraform and Jenkins.

## Contents
- `app.py` → Core Flask application logic.
- `templates/` → HTML templates for the frontend.
- `requirements.txt` → Python dependencies.
- `Dockerfile` → Containerization setup for the Flask app.

## Purpose
- Acts as the **application layer** of the project.
- Deployed automatically on an EC2 instance provisioned via Terraform.
- Integrated into a Jenkins pipeline for CI/CD.

## How It Fits in the Project
1. Jenkins builds and tests the Flask app.
2. Docker image is created and pushed to a registry.
3. Terraform provisions infrastructure and deploys the containerized Flask app.

---
