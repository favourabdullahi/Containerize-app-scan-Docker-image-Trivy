Password Strength Checker – Dockerized and Scanned with Trivy

This project is a simple Python based password strength checker that I built to evaluate the security of user entered passwords. I containerized the application using Docker and scanned the resulting image for vulnerabilities using Trivy.

 Project Workflow

1. Built the Application
   I wrote a Python script that checks password strength based on length, character variety, and common patterns.

2. Containerized the App
   I created a Dockerfile to package the application into a Docker image .
3. Scanned for Vulnerabilities
   After installing Trivy, I scanned the Docker image to identify any security issues,in which I found 58! Vulneralibities that all came from the dependencies.

4. Version Controlled and Pushed to GitHub
   I initialized a Git repository, committed the code, and pushed it to GitHub for version control and collaboration.
