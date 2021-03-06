# Twitter CI/CD App with AWS Cloud Production Pipeline

## Highlights

- Security with JWT
- Used Docker-compose for fast container spin ups
- Leveraged Amazon Elastic Container Registry (ECR) image registry to store built images
- Configured AWS CodeBuild to run automatically when code is pushed in GitHub
- Configured an Application Load Balancer (ALB) along with ECS to run a set of microservices
- Enabled Log storage in AWS CloudWatch

## Microservices

- backend: the back-end Flask app
- frontend: the front-end React app
- Db: mongo. local db or Mongo DB Atlas

## Clone the project

```sh
git clone https://github.com/Vidhi-95/TwitterApp.git
```

## Requirements

- Node.js
- AWS Account
- Python
- VS Code

## Run the application

- Use ALB DNS name to run the application

## Major AWS Services Used

- ECR : Elastic Container Registry
- AWS Code Build
- ECS : Elastic Container Service
- ALB : Application Load Balancer
- IAM : Identity and Access Management
- Cloud Watch

## Author

- Vidhi Nagda
