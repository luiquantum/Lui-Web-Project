# Deploying a Java Web App with AWS CI/CD

This project shows how to develop a Java web app with AWS CI/CD pipeline

<br>

## Contents
* [Intro](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)
* [Contact](#contact)
* [Final Points](#final-points)

<br>

## Intro
I will be creating and deploying a Java-based web app using AWS CI/CD tools.
My goal is to learn and master the process of using technologies used in the DevOps field.  

<br>

## Technologies
These are the tools needed for this project:

- **Amazon EC2**: Using an EC2 instance to develop a web app including the creation of Key Pairs.
- **VSCode**: Chosen as my preferred IDE. Used mainly to connect to my EC2 using SSH connection.  Also, very useful for installing Apache Maven and Java, using the VSCode terminal. 
- **GitHub**: Chosen as my storage repo
- **AWS CodeArtifact**: Code Artifact will store my artifacts and dependencies.
- **AWS CodeBuild**: CodeBuild will compile the source code, run tests, and produce ready-to-deploy software packages automatically
- **AWS CodeDeploy**: This will automate my deployment process across EC2 instances. 
- **AWS CodePipeline**: CodePipeline will automate the entire process from GitHub to CodeDeploy into one efficient workflow

<br>

## Setup
1. Clone the repository
git clone https://github.com/luiquantum/nextwork-web-project.git

2. Navigate to the project directory:
cd network-web-project

3. Install dependencies:
mvn install

<br>


## Contact
You can reach me at [luighino.quintanilla@gmail.com](mailto:luighino.quintanilla@gmail.com)
- Visit my [LinkedIn](https://www.linkedin.com/in/luighi-quintanilla-b5419367/) page

<br>

## Final Points
Social media platforms like instagram are Java-based web apps, and this project shows the foundation on how to start building one by using AWS EC2 instances, VSCode, and GitHub.