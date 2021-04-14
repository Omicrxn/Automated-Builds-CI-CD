This is a research created by Alejandro Ávila Rodríguez ([Omicrxn](https://github.com/Omicrxn)) for Project II subject in the Bachelor's degree in Videogame Design and Development at UPC/CITM University. The teacher supervising this project is Ramon Santamaría ([Raysan5](https://github.com/raysan5)).

# Automated Builds and Dev Ops
The process of building in software development describes the conversion of files and other assets to create a software product that works in its intended final form. Although it can differ between programming languages or frameworks, this procedure includes compiling source files, packaging compiled files into compressed formats, producing installers and creating or updating database schemas if needed. Hence, automated builds are generated whenever the prerequisites mentioned above can be repeated at any time, do not require human intervention, and only use the information contained in the source code. Build automation is a prerequisite to Continuous Integration since it is used by CI to detect issues early, that allows Continuous Testing and Continuous Delivery to be possible, however, this will be seen further in the research. The combination of those three processes along with other practices and tools that allow organizations, teams and developers to deliver software faster and more efficiently than in traditional development is named DevOps. To sum up, DevOps is a group of techniques in which automated builds, CI and CD are contained that allow developers to deploy high-speed quality products.

# What is CI/CD
CI/CD pipelines are one of the best practices for DevOps because they deliver code changes with more reliability and speed. Continuous integration (CI) and continuous delivery (CD) are a set of practices that make possible for developers and teams to deliver more solid code changes and with more regularity. This method also known as CI/CD pipeline allows developers to focus on quality, requirements and security since the building and deployment are automated. A Continuous Integration process is a software development procedure in which all code changes are merged into a central repository multiple times a day.  Continuous Delivery is a project management practice that automates the entire release process in addition to Continuous Integration.

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

# Market Study: Choosing the best CI/CD tool
Recently, DevOps have been given more and more importance and thanks to that many tools to help with your deployments have appeared. The tool you choose may depend on your project needs, programming language or your personal preference. However some of the best choices to look at are:
## 1. GitHub Actions
GitHub Actions is a CI/CD tool provided within GitHub. Workflows can be automated, customized, and executed right within GitHub repositories, which added to the generous free tier makes GitHub Actions the best tool for testing CI/CD pipelines and for small projects. The free plan includes a 500 Mb storage and 2.000 minutes per month (minute consumption may be different from one OS to another). However it includes more pricing plans to adapt to your necessities. You can calculate the minute and storage spending as well as other information for the plans at the following [Link](https://docs.github.com/en/github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-github-actions#calculating-minute-and-storage-spending).

## 2. Jenkins
Jenkins is an open-source and free automation server where the central build and CI process takes place. It supports the construction, deployment and automation of your projects helped by hundreds of plugins. Some of the key features are that it is has a really easy installation in the most used OS, it's interface is really userfriendly, it has a huge growing community which at the same time develops plugins to use in Jenkins.

## 3. Circle CI
This tool enables automation across the user's pipeline in all the stages. One key benefit of it is that you can easily integrate CircleCI with GitHub and Bitbucket to create builds whenever you push a new commit with new code lines. It uses a container or virtual machine to build, it has a fast testing and deployment is continuous and branch-specific. Another great feature of it is that it is quite customisable and has a fast setup and unlimited construction. It has three plans, one free, one starting at 30$/month and another customizable plan to support enterprise needs. The free plan however is good for simple projects or testing, it can only run 1 job at a time and has a 2,500 free credits a week (credits are used to pay for the team's usage). If your project is Open-Source it also offers three more free containers.

## 4. GitLab

GitLab is another popular tool for DevOps which is based on the web and also features a Git repository manager. It has a very competitive free plan bringing you most of GitLab's potential with 400 minutes of CI/CD per month. It may be another great option for begginers who want to get their hands dirty on the DevOps world without paying.

# Setting Up a CI/CD environment with GitHub Actions
Even though there are multiple tools reviewed above, this explanation will be shown using GitHub Actions. However it is highly encouraged to do your own research of other tools that may adapt to your needs better.



