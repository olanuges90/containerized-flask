# Containerizing a Python Flask App With Docker and Deploy On AWS Using Amazon ECS, API Gateway and Elastic load balancer (ELB)

## Project Overview

This project focuses on containerizing a Python Flask Application for Sports API management using Docker and deploying it on AWS with a robust, scalable architecture. The deployment leverages Amazon ECS (Fargate) for container orchestration, an Elastic Load Balancer (ELB) for distributing traffic across multiple containers, and API Gateway for exposing the application’s REST endpoints securely. This setup ensures high availability, scalability, and efficient handling of incoming requests, making the application production-ready.

## Architectural Diagram
<img width="1094" alt="Screenshot 2025-01-27 at 4 03 07 AM" src="https://github.com/user-attachments/assets/7b688e7b-1564-4a9b-920f-a779f961ef29" />

## Features
- Containerized Python Flask application and its dependencies into a lightweight, portable Docker container.
- Deployment on AWS ECS (Fargate).
- Ensures even traffic distribution across multiple container instances using Elastic Load Balancer (ELB).
- Exposes RESTful API endpoints of the Flask application securely.
- Amazon ECR for Docker Image Management.
- API management and routing using API Gateway
- Esposes Application's REST API endpoints securely.

## PreRequisites
- SerpAPI: Signup for Free account and subscribe for API key.
- AWS Free account with appropriate roles for user: (i.e AmazonEC2ContainerRegistryFullAccess).
- AWS CLI with Installed and Configured to interact with AWS account.
- SerAPI Library Installed.
- Docker Desktop Installed:To Build Docker file and Push Docker Images.

## Technological Stacks
- AWS Cloud Platform
- AWS Core Services: Amazon ECS (Fargate), Elastic Load Balancer (ELB), Amazon ECR, API Gateway
- Containrization Service: Docker
- Programming Language: Python 3.x
- IAM Security ( Principle of Least Priviledge for AWS Core services)

## Set Up Instructions








