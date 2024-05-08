# DevOps Project 1: Docker Image Deployment to AWS ECR via Jenkins Pipeline

I'm excited to share the final result of my recent work in DevOps. This project marks a big step in creating deployment processes that are both effective and can grow easily.

## Project Overview
The objective was to automate the building and deployment of a Docker image to Amazon Web Services' Elastic Container Registry (AWS ECR) utilizing a Jenkins Pipeline. This initiative is designed to streamline the continuous integration/continuous deployment (CI/CD) process for Node.js applications.

## Implementation Steps
The process encompassed several critical stages:

  ✅ **EC2 Configuration**: Provisioning and setting up an Amazon EC2 instance to serve as the build server.                                                         
  ✅ **Java Installation**: Ensuring the EC2 instance runs Ubuntu 22.04 LTS and installing the necessary Java Development Kit (JDK).
  ✅ **Jenkins Setup**: Installing and configuring Jenkins on the Ubuntu server to orchestrate the pipeline.                                                         
  ✅ **Docker Installation**: Adding Docker to the server, enabling containerization of the application.
  ✅ **Jenkins Configuration**: Fine-tuning Jenkins settings for optimal performance and integration with AWS services.
  ✅ **AWS Credentials**: Securely storing AWS credentials within Jenkins to facilitate seamless interaction with AWS services.
  ✅ **Plugin Integration**: Enhancing Jenkins with plugins to support various stages of the pipeline.
  ✅ **Pipeline Execution**: Crafting a Jenkinsfile to define the pipeline steps for building a Node.js Docker image.
  ✅ **Image Deployment**: Automating the push of the built image to AWS ECR, ensuring it's ready for deployment.

This guide is designed to navigate you through the project's details, offering a blueprint for those interested in adopting a similar approach to DevOps practices. It serves as an invitation to replicate and tailor these processes to fit other innovative DevOps projects.
