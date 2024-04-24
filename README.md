# Operating-Systems-Final-Docker

Docker Challenge Project: Challenges 3 and 4

This repository (https://github.com/Anthony7145/Operating-Systems-Final-Docker/edit/main/README.md) contains my solutions for Challenges 3 and 4 of the Docker challenge series. The challenges involve setting up a full-stack application using Docker Compose (Challenge 3) and scaling up a service within the Docker environment (Challenge 4).

Challenge 3 – Full Stack Application
Objectives
Set up a multi-container application using Docker Compose.
Integrate web server, Node.js application, and database services.
Utilize environment variables for configuration.

Steps Taken:
Cloned Repository
Cloned the project repository from the provided template (https://github.com/eduluz1976/docker-challenge-template).

Navigated to Challenge 3 Folder by writing the command "cd C:\Users\antho\OneDrive\Documents\Operating-Systems-Final-Docker\Challenge 3"

Added Configuration Files
Created .env file with appropriate configuration variables.
Configured docker-compose.yml to include nginx, node-service, and db services.

Started Docker Containers by writing the command "docker-compose up -d"
Verified Services:
Accessed http://localhost:8080/api/books in the browser to test the application.

Checked running containers using "docker-compose ps"



Challenge 4 – Scaling Up an Application
Objectives
Scale the node-service to multiple instances
Understand the benefits of scaling services in Docker

Steps Taken:
1) Navigated to Challenge 4 Folder by typing "cd C:\Users\antho\OneDrive\Documents\Operating-Systems-Final-Docker\Challenge 4"
2) Scaled Node Service: docker-compose scale node-service=3
3) Verified Scaling:
   Tested load balancing by accessing http://localhost:8080/api/stats multiple times.
Checked running instances using: docker-compose ps

