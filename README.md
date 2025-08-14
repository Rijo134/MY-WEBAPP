# 🚀 7-Day DevOps Challenge – AWS CI/CD Pipeline

This repository contains all the code, configuration, and documentation for the **7-Day DevOps Challenge**, where we build a **complete CI/CD pipeline** from scratch using AWS services.

## 📌 Overview
Over 7 days, we will design and implement a fully automated **Code Commit → Build → Deploy → Production** pipeline.  
By the end of this challenge, you will have:

- ✅ Built a complete CI/CD pipeline using **AWS Developer Tools**
- ✅ Automated testing and deployment of a real application
- ✅ Created **portfolio-ready documentation** to showcase your DevOps skills

## 🛠 AWS Services Used
- **Amazon EC2** – Hosting our web application
- **AWS CodeCommit** / **GitHub** – Source code repository
- **AWS CodeArtifact** – Dependency management
- **AWS CodeBuild** – Application build & test automation
- **AWS CodeDeploy** – Automated deployment to EC2
- **AWS CodePipeline** – Full CI/CD orchestration
- **AWS CloudFormation** *(Optional)* – Infrastructure as Code

## 📅 Project Roadmap

| Day | Project | Description |
|-----|---------|-------------|
| 1️⃣ | **Set Up a Web App in the Cloud** | Launch a web application on AWS EC2 |
| 2️⃣ | **Connect GitHub Repo with AWS** | Link source control to AWS |
| 3️⃣ | **Store Dependencies in CodeArtifact** | Manage app dependencies securely |
| 4️⃣ | **Package an App with CodeBuild** | Automate builds and tests |
| 5️⃣ | **Deploy an App with CodeDeploy** | Push updates to production |
| ⭐️ | **(Optional) Automate Infrastructure** | Use CloudFormation templates |
| 7️⃣ | **CI/CD with CodePipeline** | Complete automated pipeline |

## 📂 Repository Structure
├── day1-setup-webapp/ # EC2 setup and initial deployment
├── day2-connect-github/ # GitHub & AWS integration configs
├── day3-codeartifact/ # Dependency storage & setup
├── day4-codebuild/ # Buildspec files for CodeBuild
├── day5-codedeploy/ # AppSpec files for CodeDeploy
├── day6-cloudformation/ # Infrastructure as Code templates
├── day7-codepipeline/ # Full CI/CD pipeline configuration
└── README.md # This documentation


## 🚦 Prerequisites
Before starting, ensure you have:
- An **AWS Account** ([Sign up here](https://aws.amazon.com/))
- A **GitHub account**
- Basic knowledge of Git commands
- AWS CLI installed ([Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html))

## 📖 How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/Rijo134/my-webapp.git
   cd 7-day-devops-challenge
