# Production-grade, cloud-native eCommerce application built on AWS

<!-- Row 1: Status - Most Important -->
[![Release](https://img.shields.io/github/v/release/subhamay-bhattacharyya/aws-bedrock-faq-chatbot?label=Release)](https://github.com/subhamay-bhattacharyya/aws-e-commerce-application)&nbsp;[![Release Workflow](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot/actions/workflows/release.yaml/badge.svg)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot/actions/workflows/release.yaml)&nbsp;[![Issues](https://img.shields.io/github/issues/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot/issues)&nbsp;[![Last Commit](https://img.shields.io/github/last-commit/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot/commits)

<!-- Row 2: Code Quality -->
[![Top Language](https://img.shields.io/badge/Languages-Python%20%7C%20YAML-blue)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)&nbsp;[![Commits](https://img.shields.io/github/commit-activity/t/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot/commits)

<!-- Row 3: Tech Stack -->
[![CloudFormation](https://img.shields.io/badge/CloudFormation-IaC-orange?logo=amazonaws&logoColor=white)](https://aws.amazon.com/cloudformation/)&nbsp;[![Built with Claude Code](https://img.shields.io/badge/Built_with-Claude_Code-D97757?logo=anthropic&logoColor=white)](https://claude.ai/)

<!-- Row 4: Repository Info -->
[![Files](https://img.shields.io/github/directory-file-count/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)&nbsp;[![Repo Size](https://img.shields.io/github/repo-size/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)&nbsp;[![Release Date](https://img.shields.io/github/release-date/subhamay-bhattacharyya/aws-bedrock-faq-chatbot)](https://github.com/subhamay-bhattacharyya/aws-e-commerce-application)

<!-- Row 5: Custom Metrics -->
[![Custom Endpoint](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/bsubhamay/2c71ea1cc76676b71c2fd58399441c63/raw/aws-bedrock-faq-chatbot.json)](https://gist.github.com/subhamay-bhattacharyya/2c71ea1cc76676b71c2fd58399441c63)

In this hands-on course, you design and deploy a production-grade, cloud-native eCommerce application on AWS, from scratch. It is not a toy project and not a single-service demo. It is a full-stack, microservices-based application that mirrors what Solutions Architects and Cloud Engineers build every day.

## What You Will Build

A complete eCommerce platform made of:

- A **React** frontend
- **Microservices** backend services, each packaged as a Docker container
- **NoSQL** (DynamoDB) and **relational** (RDS PostgreSQL) databases
- **Authentication** and exposed **APIs**
- A **Content Delivery Network** for the frontend
- **Integration** and **notification** flows

Every layer runs on AWS using industry-standard practices.

## AWS Services

| Area | Services |
| ---- | -------- |
| Networking | VPC, Subnets, Security Groups, NAT Gateway |
| Frontend | S3, CloudFront, Route 53 |
| Authentication | Cognito User Pools |
| Compute | ECS on Fargate (containerized microservices) |
| API Layer | API Gateway (HTTP API), VPC Link, Application Load Balancer |
| Databases | DynamoDB (catalog and cart), RDS PostgreSQL (users and orders) |
| Messaging | SNS, SQS, SES (event-driven notifications) |
| Security and Management | IAM, CloudWatch, Systems Manager |

## Architecture Focus

Most courses teach individual services. This one teaches architecture: why each service fits the overall design, and how networking, compute, storage, security, and messaging connect.

## Who Is This For?

Developers, cloud engineers, and anyone who wants real-world, hands-on AWS experience. The project is also strong material for job interviews.

## Learning Outcomes

By the end of the course you will have:

- A fully deployed eCommerce application running on AWS
- Hands-on experience with core AWS services working together
- The confidence to design and build similar architectures independently


## License

MIT
