# DevOps Project 1: Docker Image Deployment to AWS ECR via Jenkins Pipeline

I'm excited to share the final result of my recent work in DevOps. This project marks a big step in creating deployment processes that are both effective and can grow easily.

## Project Overview
The objective was to automate the building and deployment of a Docker image to Amazon Web Services' Elastic Container Registry (AWS ECR) utilizing a Jenkins Pipeline. This initiative is designed to streamline the continuous integration/continuous deployment (CI/CD) process for Node.js applications.

## Implementation Steps
The process encompassed several critical stages:

- **EC2 Configuration**: Set up an Amazon EC2 instance to function as the build server.
- **Java Installation**: Installed Java Development Kit (JDK) on an EC2 instance running Ubuntu 22.04 LTS.
- **Jenkins Setup**: Configured Jenkins on the Ubuntu server to manage the CI/CD pipeline.
- **Docker Installation**: Integrated Docker into the server for application containerization.
- **Jenkins Configuration**: Optimized Jenkins for enhanced performance and AWS services integration.
- **AWS Credentials**: Stored AWS credentials in Jenkins for efficient AWS services interaction.
- **Plugin Integration**: Added plugins to Jenkins to support various pipeline stages.
- **Pipeline Execution**: Created a Jenkinsfile to outline the steps for building a Node.js Docker image.
- **Image Deployment**: Automated the deployment of the Docker image to AWS ECR for production readiness.

This guide is designed to navigate you through the project's details, offering a blueprint for those interested in adopting a similar approach to DevOps practices. It serves as an invitation to replicate and tailor these processes to fit other innovative DevOps projects.
