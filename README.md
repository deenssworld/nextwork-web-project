# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD Tools.

<br>

## Table of Contents
-[Introduction](#Introduction)
-[Technology](#technology)
-[Setup](#setup)
-[Contact](#contact)
-[Conclusion](#conclusion)

<br>

## Introduction
This project is used for introduction to creating and Deploying a Java-based web app using AWS, especially their C/CD tools.

The deployment pipeline i am building around the Java web app in this repository is invisible to the end -user, but makes a big impact by automaing the software release processes.

- i am doing this project to learn more about CI/CD and get hands on experience in automating the code from developing codes to deploy we app. 
- This fit into my career goals because i ant to be become a devops engineer this year.

<br>

Here 's what i am using for this project:

- **AMAZON EC2**: i'm developing my web app on an Amazon EC2 virtual server, so that software developement and happens entirely in the cloud.
    - keypairs, SSH connections. install Git, Maven and Java to generate the webapp on the Ec2 instance.
- **VSCode** : For IDE, i chose Visual Studio Code. It connects directly to my developement EC2  instance , making it easy to edit  code and manage files in the cloud.
- **GitHub** : All my web app code is stored and versioned in This GitHub repository.
- **[COMING SOON] AWS Code Artifacts** : once its rolled out, CodeArtifacts will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **[COMING SOON] AWS CodeBuild** Once it's rolled out, CodeBuild will gtake over my building process. It will compile the source code , run tests, and produce ready-to-deploy software packages automatically.
- **[COMING SOON] AWS CodeDploy** Once rolled out, CodeDeploy will automate my deployment process across EC2 instances.
- **[COMING SOON] AWS CodePipeline** Once rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating Build , test and deployment
steps into one efficient workflow.

<br>

## Contact
if you have any question or comments abou my CI/CD project, please contact Don - [nurudeen.daramola@AOL.com]

- linkedIn [www.linkedin.com/in/nurudeen-daramola-4a52182a5]

## Conclusion
Thank you for exploring this i will continue to build this pipeline and apply my learning to future projects.

A big shout to **[nextwork][https://learn.nextwork.org/app]** for their project
