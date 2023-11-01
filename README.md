# Arianit Mentorship Project

Spring Microservice Deployment using Docker, docker-compose, Spring Cloud Gateway, GitHub Actions, and Pub/Sub Notifications

## Project Overview

This project involves building and deploying a Spring microservice architecture that uses Pub/Sub notifications to send information to users. The microservice architecture will be composed of two microservices: a user service and a product service. The user service will be responsible for managing user accounts and authentication, while the product service will be responsible for managing product data. The Spring Cloud Gateway will act as a single entry point for both microservices.

### Pub/Sub Notifications

Pub/Sub notifications is a messaging service that allows you to send and receive messages between independent applications. In this project, we will use Pub/Sub notifications to send notifications to users when certain events occur, such as when a new product is added or when a user's account is updated.

### Building and Deploying the Microservices

To build and deploy the microservices, you will need to have Docker and docker-compose installed on your machine. You will also need to create a GCP account and enable the Pub/Sub API.

Once you have all of the prerequisites installed, you can follow these steps to build and deploy the microservices:

1. Clone this repository to your local machine.
2. Build and deploy the microservices using Docker and docker-compose.

### Configuring GitHub Actions for CI/CD

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your development and deployment workflows. In this project, we will use GitHub Actions to automate the build, test, and deployment of the microservices.

To configure GitHub Actions for CI/CD, you will need to create a GitHub Actions workflow. The workflow will define the steps that you want to automate, such as building the microservices, running tests, and deploying the microservices.

### Sending Notifications

To send notifications, you will need to use the Pub/Sub Client library in your microservices. The Pub/Sub Client library allows you to publish messages to Pub/Sub topics.

To publish a message to a Pub/Sub topic, you will need to create a Publisher object. The Publisher object allows you to publish messages to a specific topic.

Once you have created a Publisher object, you can call the publish() method to publish a message to the topic. The publish() method will return a Future object. The Future object will allow you to track the status of the message publication.

### Receiving Notifications

To receive notifications, you will need to subscribe to the Pub/Sub topics in your applications. You can use the Pub/Sub Client library to subscribe to topics and receive messages.

To subscribe to a Pub/Sub topic, you will need to create a Subscriber object. The Subscriber object allows you to subscribe to a specific topic and receive messages when they are published.

Once you have created a Subscriber object, you can call the listen() method to subscribe to the topic. The listen() method will return a Future object. The Future object will allow you to track the status of the subscription.

## Conclusion

This project is a great opportunity to learn about microservices architecture, deployment using Docker, docker-compose, Spring Cloud Gateway, GitHub Actions, and Pub/Sub notifications. The project is also a valuable opportunity to gain hands-on experience with these technologies.

### Additional Information

* For more information about Spring microservices, please see the following documentation: https://docs.spring.io/spring-boot/docs/current/reference/html/
* For more information about Spring Cloud Gateway, please see the following documentation: https://spring.io/projects/spring-cloud-gateway
* For more information about GitHub Actions, please see the following documentation: https://docs.github.com/en/actions
* For more information about Pub/Sub notifications, please see the following documentation: https://cloud.google.com/pubsub
