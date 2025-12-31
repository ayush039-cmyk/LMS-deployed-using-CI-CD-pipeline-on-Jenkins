# LMS-deployed-using-CI-CD-pipeline-on-Jenkins

This project is a Library Management System web application with automated CI/CD pipeline using Jenkins. It demonstrates how code changes in GitHub can automatically trigger builds, tests, and deployment.

## Features

User-friendly interface to manage books, users, and transactions.

Add, update, delete, and search books.

Track borrowed and returned books.

Automated CI/CD pipeline for continuous integration and deployment.

Dockerized Jenkins environment for consistent builds.

## CI/CD Pipeline

The Jenkins pipeline automates the following steps:

Code Checkout: Pull the latest code from GitHub repository.

Environment Setup: Create Python virtual environment or install dependencies globally.

Dependency Installation: Install Python packages from requirements.txt.

Automated Testing: Run unit tests to ensure code correctness.

Build & Deployment: Build the application and deploy to the target server or Docker container.

Trigger: Jenkins automatically runs the pipeline whenever a commit is pushed to GitHub via webhooks.
