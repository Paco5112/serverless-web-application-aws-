# Serverless To-Do Application

This project is a serverless web application built using AWS services. The app allows users to perform CRUD (Create, Read, Update, Delete) operations on a to-do list. It leverages AWS Lambda, API Gateway, and DynamoDB for a scalable, cost-effective architecture.

## Key Features
- **Serverless Architecture:** Deployed using AWS Lambda, API Gateway, and DynamoDB.
- **RESTful API:** Exposes public endpoints for managing to-do tasks.
- **Python (boto3):** Used for Lambda function code to interact with DynamoDB.
- **Infrastructure as Code (IaC):** Deployment automated using Terraform.

## Endpoints
- `POST /todos` - Create a new to-do
- `GET /todos` - Retrieve all to-dos
- `PUT /todos/{id}` - Update a to-do by ID
- `DELETE /todos/{id}` - Delete a to-do by ID

## Technologies
- AWS Lambda
- API Gateway
- DynamoDB
- Python
- Terraform

## Getting Started
1. Clone the repository
2. Deploy the infrastructure using Terraform
3. Test the API using Postman or curl
