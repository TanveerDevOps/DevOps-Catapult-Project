# DevOps-Catapult-Project
This project is a part of DevOps catapult programme.
Here I've used one sample application, to build and deploy to Docker.


### Technology Used
Git, Jenkins, Maven, Sonarqube, Ansible, DockerHub, Docker, AWS.

### Description
This is an auto generated maven project deployment. The Goal of this project is to demonstrate the CI/CD pipeline. There are various stages in the pipeline, first it checkout the code from the github, then performs maven build on the code, then takes the war generated from the maven build and create an image and push it to Docker Hub.
After that using ansible playbook, it's retrieving the image from docker hub and deploying it docker and run the container.

AWS infrastructure has been used for this project demonstration.

This application can be retrieved at: http://hostname:8080/my-app/
