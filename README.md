# 3.11-assignment submission

## Instructions:

1. Create a new Node.js application using the Express framework.
2. Set up automatic testing for the application using a testing framework such as Jest or Mocha.
3. Create a code repository for the application on a version control system such as Git.
4. Create a Dockerfile for the application that includes all necessary dependencies.
5. Set up a CI/CD pipeline using a tool such as Github Action.
6. Configure the pipeline to automatically build the Docker image and run the tests whenever changes are pushed to the code repository.
7. Push the Docker image to a container registry such as Docker Hub or AWS ECR.
8. Set up a task definition and service in Amazon Elastic Container Service (ECS) to deploy the containerized application.
9. Configure the pipeline to automatically deploy the containerized application to ECS whenever changes are pushed to the code repository and all tests pass.
10. Write a documentation explaining the steps you have done, including the tools and services used.

## Deliverables:

The Node.js application with automatic testing set up
Code repository with the CI/CD pipeline configured
Dockerfile and configuration files for ECS
Documentation explaining the steps taken to set up the pipeline.

## Steps taken:

1. Create ECR in AWS console - 
![Screenshot 2023-09-02 at 4 10 53 PM](https://github.com/vincent8055/3.11-assignment/assets/127754761/7e8c86ab-f42f-41a2-a1aa-aad3fc265233)


2. Create ECS in AWS console and define task definition
![Screenshot 2023-09-02 at 4 14 30 PM](https://github.com/vincent8055/3.11-assignment/assets/127754761/a49bea8d-a36a-4e52-af0b-6614b24d1073)


3. create CI/CD pipeline to deploy Dockerfile in Github actions.

