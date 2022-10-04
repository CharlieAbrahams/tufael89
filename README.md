#App Project

##Introduction
This project is a culmination of the following:
  **Project Management
  Python Fundamentals and Testing
  Git
  Linux
  Python Web Development
  Databases
  Continuous Integration and Deployment (CI/CD)
  Azure Cloud Fundamentals
  Containerisation**

##Overview 
I am going to create a simple **web application** that integrates with a **SQL database** and demonstrates **CRUD functionality** 
Use **container instances**
To create a **continuous integration (CI)/continuous deployment (CD) pipeline** that will automatically **test, build and deploy** the application

##Project Management and Version Control
Technologies for Project management and version control:
  ###**Jira**
  To be used to track the project using Agile Scrum methods listed below:
    MoSCoW prioritisation
    Estimation of efforts
    User Stories
  ###**Git and Guthub**
  Git as version control system and code repository to be hosted on GitHub. Feature branch model to be used.
  produce a risk assessment to identify and analyse any potential risks to your application and infrastructure.

##Application
Technologies:
  **Python
  Pytest
  Flask
  Docker/Docker Compose
  MySQL/SQL Lite**

Create Web application using Flask framework
CRUD functionality 
ERD to illustrate relationships between entities and modelled in the database

###Application
The application is a monolithic **Flask application** that serves both the frontend and backend of the application
The frontend aspect of the app will use HTML templates to serve the web pages that allow the user to perform CRUD functionality with information from the database
The backend aspect of the application will use SQL Lite to model and integrate with the database

This application will be hosted in a container to allow it to be deployed to a **Docker Swarm**

###Database
Application to interface with separate database service - **SQL Lite**
The database must contain two tables with a relationship
The relationship must at least be one-to-many 

###Testing 
Unit tests must be written for the application to achieve high coverage
**pytest** to write and test the application

##CI/CD Pipeline
Automate the integration and deployment of new code
Automation server is **Jenkins**
CI/CD Pipeline must: 
  Run unit tests
  Build the Docker images
  Push the Docker images to a registry
  Deploy to a Swarm

Pipeline to be triggered when new code to be pushed onto GitHub repository. Achieved by **GitHub Webhook**

##Deployment
The application should be deployed to a **Docker Swarm** hosted in the cloud.
One manager node and one worker node. Neither of these nodes should be the Jenkins build server.



