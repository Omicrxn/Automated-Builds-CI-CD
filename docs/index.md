# Introduction
CI/CD pipelines are one of the best practices for DevOps because they deliver code changes with more reliability and speed.

# What is CI/CD
Continuous integration (CI) and continuous delivery (CD) are a set of practices that make possible for developers and teams to deliver more solid code changes and with more regularity. This method also known as CI/CD pipeline allows developers to focus on quality, requirements and security since the building and deployment are automated.
A Continuous Integration process is a software development procedure in which all code changes are merged into a central repository multiple times a day. 
Continuous Delivery is a project management practice that automates the entire release process in addition to Continuous Integration.
With CI, each 

# Elements of a CI/CD pipeline

An CI/CD pipeline is a proven set of processes that allow developers to deliver new versions of software. Those steps would still have to be performed by humans if there were no automated pipeline. There are commonly a couple of stages involved in software releases:
## Source stage
The pipeline run is initiated by a source code repository. Whenever a change in code is detected the CI/CD tool runs the pipeline. Furthermore, triggers can be automatically scheduled or initiatied by the user.
## Build stage
We merge the source code and its dependencies to create a working version of our software that we will ultimately deliver to our customers. Depending on the programming language we use, compilation may be required or not in this step. Cloud-native software is typically deployed with Docker, which is a service that allow us to deliver software packages (called containers) which are isolated between them. This allow us to separate our applications from our infrastructure to deliver the product quickly.
## Test stage
During this stage, we execute automated tests to verify the validity of our program and the functionality of our service. This stage serves as a protective shield, preventing quickly reproducible errors from affecting consumers. It is the developers' duty to write the tests and it is a great practice to do so while we are adding new features to the program.
## Deploy stages
Finally, now that we have a build that has passed all our tests we are ready to deploy the program. The software can be deployed to the users in a production state or it can also be deployed internally as an alpha or a beta. 

# Why use a CI/CD pipeline
Using a pipeline can bring to the team and to the final product a lot of benefits. The most notorious one is that developers doesn't need to loose time doing all those steps since it is automated and they can focuse on other things like improving the code quality, or writing new features. It is also benefitial to the QA team since they can have access to the latest version of the system which has passed all the tests setted by the developers and that means that some errors have already been taken care of. CI/CD pipelines allow to roll back to a previous version very easily.

# Choosing the best CI/CD tool
Recently, DevOps have been given more and more importance and thanks to that many tools to help with your deployments have appeared. The tool you choose may depend on your project needs, programming language or your personal preference. However some of the best choices to look at are:
## 1. Jenkins:
Jenkins is an open-source and free automation server where the central build and CI process takes place. It supports the construction, deployment and automation of your projects helped by hundreds of plugins. Some of the key features are that it is has a really easy installation in the most used OS, it's interface is really userfriendly, it has a huge growing community which at the same time develops plugins to use in Jenkins.

## 2. Circle CI
This tool enables automation across the user's pipeline in all the stages. One key benefit of it is that you can easily integrate CircleCI with GitHub and Bitbucket to create builds whenever you push a new commit with new code lines. It uses a container or virtual machine to build, it has a fast testing and deployment is continuous and branch-specific. Another great feature of it is that it is quite customisable and has a fast setup and unlimited construction. It has three plans, one free, one starting at 30$/month and another customizable plan to support enterprise needs. The free plan however is good for simple projects or testing, it can only run 1 job at a time and has a 2,500 free credits a week (credits are used to pay for the team's usage). If your project is Open-Source it also offers three more free containers.

## 3. GitLab && Buddy

GitLab and Buddy are two more tools which are compatible with GitHub and Bitbucket. They both offer a good free plan and have a git environment ready for you to use. The two offer you to build jobs with Docker containers and are highly used by developers. However Buddy might have less users and a smaller community but they are both good options to be included in the list.

# Setting Up a CI/CD environment


