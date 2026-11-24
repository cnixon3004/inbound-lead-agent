# Architecture

## Overview

The application will use AWS serverless
services for its core backend and n8n
for workflow automation.

## Lead Sources

1. Website contact form
2. Phone/voice agent

## Processing

1. API Gateway receives the request.
2. Lambda validates and processes the request.
3. DynamoDB stores the lead.
4. n8n coordinates AI analysis and notifications.
5. The dashboard displays lead information.

## AI

Amazon Bedrock will analyze inquiries,
extract relevant information, and generate
lead summaries.

## Infrastructure

Terraform will manage AWS resources.
