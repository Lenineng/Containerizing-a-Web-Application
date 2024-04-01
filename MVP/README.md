Project Title

Containerizing a Web Application.

Table of Contents

    Introduction
    Features
    Technologies
    Getting Started
    Prerequisites
    Installation
    Running the Application
    Docker
    Building the Docker Image
    Running the Docker Container

Introduction

This web application allows users to create, manage, and track their projects and tasks efficiently. It provides a simple and user-friendly interface for adding new tasks, viewing the list of tasks, and marking tasks as completed.
Features

    Ability to add new tasks.
    View the list of tasks.
    Mark tasks as completed.

Technologies

    HTML
    CSS
    JavaScript
    Node.js
    Docker

Getting Started
Prerequisites

    Node.js

Installation

Clone the repository:

git clone https://github.com/lenineng/Containerizing-a-Web-Application

Navigate to the project repository:

cd Containerizing-a-Web-Application

Install dependencies:

npm install

Running the Application

To run the application locally, use the following command:

npm start

Docker
Building the Docker Image

To build the Docker image for the application, use the following command:

sudo docker build -t lenineng/containerizing-a-web-application:latest .

Running the Docker Container

Once the Docker image is built, you can run a Docker container using the following command:

sudo docker run -d -p 3000:3000 lenineng/containerizing-a-web-application:latest

Pushing the Docker Container

Once logged in, you can push the tagged Docker image to Docker Hub using the docker push command:

sudo docker push lenineng/containerizing-a-web-application:latest


