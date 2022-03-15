# Daladala Rides App

A rebuild of the serverless website WildRydes Workshop in Vue.js with AWS Amplify CLI.

# The application architecture uses the following AWS services.

Lambda - Backend API compute
API Gateway - Backend HTTP interface
DynamoDB - NoSQL datastore
S3 - Object store for hosting frontend.
AWS CodeBuild for deploying static website content
Cognito - user management, authentication, and authorization.

# Implementation
1.Static Web Hosting
Deploy the static website using AWS Amplify Console by first creating a git repository (in either CodeCommit or GitHub) and then pushing the site code.
2.User Management	
Configure user management for the website using Amazon Cognito.
3.Serverless Backend	
Create an AWS Lambda function that will persist data to an Amazon DynamoDB table.
4.RESTful APIs	
Expose the Lambda function via an Amazon API Gateway as a RESTful API that the static site can call.
5.Clean up
Delete or inactivate resources on AWS to avoid incurring costs.
