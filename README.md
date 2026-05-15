# SimpleWorkflowCICD

![CI Status](https://github.com/AlexB4rbosaDevsec/SimpleWorkflowCICD/actions/workflows/maven-publish.yml/badge.svg)
![Coverage](https://img.shields.io/badge/coverage-n/a-lightgrey)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 🚀 Overview

**SimpleWorkflowCICD** is an educational project designed to **demonstrate a complete CI/CD pipeline using GitHub Actions**, without requiring external tools like Jenkins or SonarQube.  

This repository showcases a full workflow including:

- Maven build  
- Automated tests  
- Checkstyle enforcement  
- Code coverage reports with JaCoCo  
- Artifact upload and download  

> ⚠️ Note: The primary goal is to **teach workflow automation on GitHub**.  

---

## ⚠️ Disclaimer

- Some files in this repository (e.g., **Dockerfile**, environment configs) are **purely illustrative**.  
- The project itself does **not execute Docker containers or deploy services**.  
- These illustrative files were sourced from:  
[https://github.com/hkhcoder/vprofile-project/tree/docker](https://github.com/hkhcoder/vprofile-project/tree/docker)

---

## 📂 Project Structure


SimpleWorkflowCICD/
├── .github/
│   └── workflows/
│       └── maven-publish.yml   # CI/CD workflow
├── src/                        # Sample Maven source code
├── pom.xml                      # Maven project configuration
├── Dockerfile*                  # Illustrative file only
└── README.md

## 🛠 Technologies & Tools


Technology	Purpose
GitHub Actions	CI/CD workflow automation
Maven	Build, tests, checkstyle
JaCoCo	Code coverage reports
Docker (optional)	Illustrative only, not used in workflow

⚡ Workflow Details
Triggered automatically on push or pull request to main.
Jobs executed:
build: Maven build and artifact generation (.jar files)
test: Run unit tests, checkstyle validation, generate code coverage
All artifacts and reports are available for download directly in the GitHub Actions interface.

🎯 Purpose
This repository serves as a hands-on, practical demonstration of a CI/CD pipeline using GitHub Actions.
It emphasizes that automating builds, tests, and artifact management can be done entirely within GitHub, with no need for external CI/CD tools.

📌 License
This project is licensed under MIT and is free for educational use.

🔗 Quick Links
GitHub Actions Workflow
Illustrative Docker files source
