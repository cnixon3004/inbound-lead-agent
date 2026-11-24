# Inbound Lead Agent — Requirements

## Project Overview

An AI-assisted lead management application
designed for small digital agencies and IT
consulting businesses.

## Business Problem

Small businesses can miss potential customers
when inquiries arrive through multiple channels
and are not followed up consistently.

## Project Goals

- Capture website inquiries.
- Capture phone inquiries.
- Store lead information securely.
- Analyze leads using Amazon Bedrock.
- Categorize and prioritize leads.
- Automate notifications using n8n.
- Provide a simple lead management dashboard.

## Initial Technology Stack

- AWS API Gateway
- AWS Lambda
- Amazon DynamoDB
- Amazon Bedrock
- Amazon SES
- n8n
- Python
- React
- Terraform
- GitHub

## Initial MVP

The first milestone is a website lead intake
API that validates and stores submissions
in DynamoDB.

## Security Requirements

- Use least-privilege IAM permissions.
- Never commit credentials or secrets.
- Validate incoming requests.
- Use synthetic customer data during development.
- Avoid logging unnecessary personal information.
