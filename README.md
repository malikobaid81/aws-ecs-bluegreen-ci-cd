# aws-ecs-bluegreen-ci-cd
This project demonstrates an automated CI/CD pipeline to deploy a containerized application to Amazon ECS using AWS CodePipeline, CodeBuild, Amazon ECR, and AWS CodeDeploy with a blue/green deployment strategy.

Overview:
Containerization: Application packaged into Docker images and stored in Amazon ECR.
CI/CD Pipeline: Automated build and deployment using AWS CodePipeline + CodeBuild.
Deployment Strategy: Blue/Green deployments managed by AWS CodeDeploy for zero downtime and safe rollbacks.
Infrastructure: ECS cluster and services configured to run containerized workloads.

Key Features:
Automated pipeline from source → build → deploy.
Zero-downtime deployments with traffic shifting.
Rollback capability if health checks fail.
Integration with Amazon ECR for image storage.

Tech Stacks:
AWS ECS (Elastic Container Service)
Amazon ECR (Elastic Container Registry)
AWS CodePipeline
AWS CodeBuild
AWS CodeDeploy (Blue/Green strategy)

Docker
