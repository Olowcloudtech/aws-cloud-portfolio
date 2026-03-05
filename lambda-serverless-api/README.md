# Serverless API with AWS Lambda

This project demonstrates how to build a serverless HTTP API using AWS Lambda and a Lambda Function URL.

## Architecture
Client (Browser/Curl) → Lambda Function URL (HTTPS) → AWS Lambda → CloudWatch Logs

## AWS Services Used
- AWS Lambda
- Lambda Function URL
- CloudWatch Logs
- IAM (execution role)
- Environment Variables

## What I Built
- Created and deployed a Lambda function (Python)
- Configured a Lambda Function URL to invoke the function via HTTPS
- Implemented GET support (queryStringParameters)
- Implemented POST support (JSON body parsing + validation)
- Configured environment variables (case-sensitive `NAME`)
- Used CloudWatch logs + Lambda console test events to debug event payloads and responses

## Key Learnings
- Lambda HTTP event structure (v2.0)
- Difference between **Deploy** and **Test** in the console
- How to return proper proxy responses (`statusCode`, `headers`, `body`)
- How to log requests and troubleshoot with CloudWatch

## Future Improvements
- Replace Function URL with API Gateway (multiple routes)
- Add DynamoDB persistence
- Add auth (IAM/JWT) + least-privilege IAM policies
