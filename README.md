# Resilient CloudOps Platform on AWS

A production-style CloudOps and DevOps project built incrementally using Python, Docker, AWS, Terraform, CI/CD, and monitoring.

## Project Goal

The goal of this project is to learn how to build, deploy, automate, monitor, and troubleshoot a cloud application using practical DevOps workflows.

## Planned Architecture

User → Application Load Balancer → EC2 Instances → Dockerized Python Flask Application → Amazon RDS PostgreSQL

## Technologies

- Python and Flask
- PostgreSQL
- Linux
- Git and GitHub
- Docker
- GitHub Actions
- AWS
- Terraform
- Amazon CloudWatch

## Project Roadmap

- [x] Build a local Python Flask application
- [x] Add health-check and API endpoints
- [ ] Connect the application to PostgreSQL
- [ ] Containerize the application using Docker
- [x] Add automated testing
- [ ] Create a GitHub Actions CI/CD pipeline
- [ ] Deploy the application to AWS
- [ ] Provision AWS infrastructure using Terraform
- [ ] Add load balancing and Auto Scaling
- [ ] Configure monitoring, logs, and alerts
- [ ] Simulate failures and document recovery steps

## Current Status

Stage 0: Repository setup and project planning.
Stage 1 completed: Flask application, health-check endpoint, automated setup, and endpoint tests.