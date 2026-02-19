# Phase 4 CI/CD Mini Pipeline – Automated Web App Deployment 🚀

## Project Overview
This project demonstrates a minimal CI/CD pipeline for a simple web application.
The goal is to showcase automation, GitHub Actions workflow, and deployment skills — perfect for interview portfolios.

   +-------------------+
   |  Developer / Git  |
   |  (push code)      |
   +---------+---------+
             |
             v
   +-------------------+
   |  GitHub Repository|
   +---------+---------+
             |
             v
   +-------------------+
   | GitHub Actions CI |
   |  - Build / Lint   |
   |  - Test           |
   +---------+---------+
             |
             v
   +-------------------+
   | Deployment Target |
   |  (GitHub Pages /  |
   |   simple server)  |
   +-------------------+
             |
             v
   +-------------------+
   | Live Web App      |
   | app/index.html    |
   +-------------------+


The app is a simple HTML page:

- app/index.html – the web app content
- Automatically deployed via GitHub Actions workflow

## Project Structure

project-6-cicd-mini-pipeline/
├── README.md            # Project documentation
├── app/
│   └── index.html       # Sample web application
└── .github/
    └── workflows/
        └── ci-cd.yml   # CI/CD pipeline definition (GitHub Actions)

## CI/CD Pipeline
The pipeline automatically:
1. Checks out the repository
2. Runs a simple build step (lint HTML or validate files)
3. Deploys the app/ folder to the target environment (e.g., GitHub Pages)

This demonstrates:
- Automated deployment
- Continuous integration and testing
- Professional GitHub workflow setup

## Local Setup & Testing
1. Clone the repository:
   git clone https://github.com/Geraldcloudguy/project-6-cicd-mini-pipeline.git
   cd project-6-cicd-mini-pipeline
2. Open the web app in a browser:
   open app/index.html   # MacOS
   xdg-open app/index.html   # Linux
   start app\index.html     # Windows
3. Check pipeline status on GitHub Actions for automated deployment.

## Future Enhancements
- Add a simple Node.js or Python backend
- Include automated testing (unit tests / HTML validation)
- Deploy to a cloud provider (AWS S3, Netlify, or similar)

## Status
![CI/CD Pipeline Status](https://img.shields.io/badge/pipeline-active-brightgreen)
