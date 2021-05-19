The full source code used in this video can be found in this GitHub project: https://github.com/abohmeed/awscicd 
Learn how to use AWS CodeCommit, CodeBuild, CodePipeline and Lambda functions to create a complete CI/CD pipeline. 
In this video will are going to do the following:
Create a sample API using NodeJS.
Build a Docker image from the application and push it to ECR.
Use CodeCommit as a Git repository to store our code.
Define our build instructions in a CodeBuild project.
Trigger the CodeBuild job automatically when code is pushed to the master branch using CodePipeline.
Write a simple test for our NodeJS app using Mocha.
Create a second CodeBuild project (QA) to apply our automated test.
Configure the CodeBuild QA project to be triggered when a Pull Request is created or modified using a Lambda function.
Provide fast feedback to the Pull Request creator by commenting on the PR with the test results using another Lambda function.
Implement Continuous Delivery (CD) by deploying an EC2 instance and configuring the CodeBuild project to deploy the Docker image to the instance and update the application using docker-compose.

