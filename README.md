# Team 1 - QA Final Group Project Repo

## Contents
1. Team Members
2. Project Background
3. The Application
4. Build Server
5. Project Management
6. Risk Assessment


## 1. Team Members:
* Arman Khan
* Beatriz Manzano
* Kazi Uddin
* Martin Taylor


## 2. Background
The team's brief was to:
1. Review the design and requirements for the PetClinic applicatrion.
2. Select the appropriate tools and application to automate both test and production installation.
3. Create a full CD/CI deployment

## 3. The Application:
PetClinic WebApp has three components
1. A front-end written in angular js 
2. A back-end restful API version of the written in java (Link). 
3. A database connected to the back-end, running on MySQL.

## 4. Build Server:
A single AWS instance running the following applications:
* Jenkins for CD/CI automation
* Ansible for instance configure
* Docker for containerisation
* Kubenetes to Deploy instances to the Evironments
* Terraform to build Environments

## 5. Project Management:
The team review the choice of available software to manage the project and descided on TRELLO. Since the begin of the project, the appointed Scrum Master has been hosting dialy meetings a 9am, recording the minutes within the TRELLO board.
![TRELLO](images/trello.PNG)

## 6. Risk Assessment:
The team conducted a simple risk assessment:
![RISKASSESSMENT](images/risk.PNG)


## Docker
the Docker had two applications, one frontend and one backend. Their images were built and containerized. The database was created on Rdb on AWS.It's container was also built on the same instance. Images of the three containers were pushed on Dokcerhub were Kubernetes would manage and build them.The environment.ts directive instructs the front end application to interface with the back end, pulling database information to display on the site and allowing CRUD capability. We used DockerHub's team repository feature so that we could all push and get images from our own accounts.

![Dockerhubimages].(

