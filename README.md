# Reference
- Doc: https://webapp.serverlessworkshops.io/0-introduction/
- GitHub Repo: https://github.com/aws-samples/aws-serverless-webapp-workshop

# DevOps
GitHub Repo: https://github.com/xueqiut/aws-serverless-workshop

TFE Pipeline: https://app.terraform.io/app/xueqiut-org/workspaces/aws-serverless-workshop

AWS Account: 
- management account: 992382444373
- Workload account: 022499001702

IAM ruser/Role
- TFE Authenticate: Key pair of tfe_user from the management account. Exported as TFE Variable Sets
- TFE Deployment Authorization: TFEWorkloadRole role to be assumed from the Workload account

Build and Run application - update npm dependencies from ^ to ~ to update patch without changing the minor version
- install python
- npm install
- npm run build
- npm run serve

# Infrastrucutre

## Static Website Hosting
Instead of Amplify, host the website with S3

## User Management

## Serverless Backend

## RESTful APIs

# Serverless web application

This workshop shows you how to build a dynamic, serverless web application. You'll learn how to host static web resources with Amazon S3, how to use Amazon Cognito to manage users and authentication, and how to build a RESTful API for backend processing using Amazon API Gateway, AWS Lambda and Amazon DynamoDB.

## Completing the workshop

The simplest way to complete the workshop is by visiting the hosted version at [webapp.serverlessworkshops.io](https://webapp.serverlessworkshops.io).

## What's Included

This repository includes the following folders:

* `deck`: PDF copies of the presentation materials for this workshop.
* `resources`: Any required sample code, IAM policies, or Cloudformation templates needed to complete the workshop.
* `workshop`: A [Hugo](https://gohugo.io) site with instructions for completing the workshop.

## Running locally

1. [Clone this repository](https://help.github.com/articles/fork-a-repo/).
2. [Install Hugo locally](https://gohugo.io/overview/quickstart/).
3. Navigate to the `workshop` directory
    ```bash
    cd aws-serverless-webapp-workshop/workshop
    ```
4. Launch the website locally with the following command:
    ```bash
    hugo serve
    ```
5. Visit `http://localhost:1313` in your browser and complete the workshop

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
SPDX-License-Identifier: MIT-0
