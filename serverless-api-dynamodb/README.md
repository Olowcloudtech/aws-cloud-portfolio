# Serverless User API (AWS)

This project demonstrates a serverless architecture using AWS services.

## Architecture

Client → API Gateway → Lambda → DynamoDB

The API retrieves user data stored in a DynamoDB table using a Lambda function.

## Endpoint

GET /users

Example request:

curl https://YOUR_API_ID.execute-api.us-east-2.amazonaws.com/users

## Example Response

[
 {"UserID":"300","City":"Chicago","Age":50,"Name":"MJ"},
 {"UserID":"200","City":"Boston","Age":42,"Name":"Sarah"},
 {"UserID":"100","City":"Markham","Age":44,"Name":"Ahmed"}
]

## AWS Services Used

- Amazon API Gateway
- AWS Lambda
- Amazon DynamoDB
- IAM

## Skills Demonstrated

- Serverless architecture
- REST API design
- DynamoDB NoSQL database
- Lambda function development
- API Gateway integration
