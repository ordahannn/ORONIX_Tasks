# ORONIX Tasks

Oronix Tasks is a cloud-based task management application built on a fully serverless architecture using AWS.
It provides users with a secure platform to create, update, and manage personal tasks, while administrators benefit from role-based access control.
The system is lightweight, scalable, and designed for seamless use across devices via a responsive web interface hosted on Amazon S3.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: AWS Lambda
- **Authentication**: Amazon Cognito
- **API Management**: Amazon API Gateway
- **Database**: Amazon DynamoDB
- **Hosting**: Amazon S3 (static website hosting)

## Project Structure

oronix-tasks/
├── frontend/ # Static site files
├── backend/ # Lambda functions
├── deployment/ # Templates, guides, and cost estimation
└── README.md

## How to Deploy

1. Deploy Cognito User Pool and configure roles.
2. Upload backend Lambda functions and connect them via API Gateway.
3. Set up a DynamoDB table for task data.
4. Upload the frontend files to an S3 bucket and enable static website hosting.
5. Update frontend endpoints to match your API Gateway.

## Notes

This project was developed in an academic setting and is intended for demonstration purposes only.

## Authors

- Or
- Roni
