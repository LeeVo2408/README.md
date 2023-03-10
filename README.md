The ultimate goal of practising Continuous Delivery (CD) is to enhance the delivery flow. In general, CD:

- Improves the speed of delivery; therefore, improve an organization's efficiency.

It is crucial to understand briefly how CD works and how it can be a powerful tool in production.

# Continuous Delivery (CD):
Continuous Delivery is a software engineering approach in which all changes are delivered quickly, safely, and sustainably. It provides an automated high-speed building and testing environment to ensure changes are *relevant*. This is achieved by ensuring that code is always in a deployable state, even with thousands of changes made daily. In short, CD automates and optimizes the repetitive tasks in the deployment process and lets human solves problems.

Benefits of implementing CD:
-	**Low-risk released**: CD identifies and addresses bugs in the earlier stages before they become significant problems later. 

-	**Improve developers' performance**: Teams have more time to focus on creating innovation instead of doing repetitive tasks. With an automated and reliable testing process, developers are more confident when pushing code into production.

-	**Delivery updates faster**: Organizations can deliver updates to customers quickly and frequently.

There are some minimum practices required, and one of them is [Continuous Integration](https://github.com/LeeVo2408/README.md/blob/main/README.md#continuous-integration) 

# Continuous Integration (CI):

>if something takes a lot of time and energy, you should do it more often, forcing you to make it less painful. 

CI is the practice of automating the integration of code changes into a mainline codebase (trunk). Developers merge code changes into a central repository where automated tests are run both before and after the merge, which ensures that the changes do not introduce bugs. 

To successfully implement CI, some of the minimum requirements are: 

-	**Trunk-based development**: Developers frequently divide their work into small branches and merge them into a trunk.

-	**Continuity**: Automated testing process.

-	**Visibility**: The status of the work should be visible to the team.

# Open-source CI/CD Tools:

There are various CI/CD tools on the market; therefore, organizations have choices to choose the most suitable tools that can be beneficial based on their needs and goals. 

The list below includes the most famous tool (1), the beginner-friendly tool (2) and the tool that is best for specific needs (3).

###### 1 . [Jenkins](https://www.jenkins.io/)
- One of the leading CI/CD tools on the market. Jenkins is a cross-platform, java-based tool that mainly supports CI operation. In addition, Jenkins can be extended via plugins, which integrate other development lifecycle operations such as build, document, deploy, and much more.

- Jenkins is one of the most famous CI tools thanks to its real-time testing and reporting on isolated changes in a larger codebase, alongside simple installation and configuration. Every source code change is built and tested. Therefore, new software is released frequently because developers only need to concentrate on a specific commit rather than the entire source code. 

Advantages:
- High security
- Easy to set up 
- It can run on all major platforms
- Huge variety of plugins  

Disadvantages: 
-	Difficult in managing plugin
-	It does not allow sever-to-server federation

###### 2.       [Buddy](https://buddy.works/)
- Buddy is a CI/CD tool that is friendly and easy to use with a simple and intuitive user interface. Using the delivery pipeline, Buddy can build, test and deploy applications.

- Buddy has more than 100 ready-to-use activities for fast deployment, allowing the best delivery in the most straightforward way, which helps developers' transition to CI/CD practices easier. It is also helpful in notifying failures in building and deploying code.

Advantages: 
-	Supporting widely used languages, frameworks, and task management 
-	Easy configuration 
-	Simple and informative User interface
-	High security 

Disadvantages
-	There is little information or documents available about this tool

###### 3.       [GitLab](https://gitlab.com/users/sign_in)
- GitLab is a collection of tools for managing various areas of the software development cycle. The core product is a web-based Git repository manager with tools for issues tracking, analytics and wiki.

- GitLab is popular among people who work on Docker-based containers and microservice. Docker??? s users can run CI/CD test jobs separated in Docker containers and create Docker images using GitLab Runner. It provides excellent pipeline control overall and integrations.

Advantages:
-	Simple configuration 
-	High security
-	Automated pipeline 
-	Allow self-hosting on any plan 

Disadvantages:
- The interface might be slower than other platforms
- Common problems with repositories


# Relevant Sources of Information 

[Implementing Continuous Delivery](https://cloud.google.com/architecture/devops/devops-tech-continuous-delivery#implementing_continuous_delivery)

[DecOps Tech: Continuous Integration](https://cloud.google.com/architecture/devops/devops-tech-continuous-integration)

[Continuous Delivery](https://continuousdelivery.com/) by Jez Humble

## About the Tools

[Best Open Source CI/CD 2022](https://hevodata.com/learn/open-source-ci-cd-tools/#O5)

[Top 14 Ci/CD tools for your DepvOps project](https://www.browserstack.com/guide/top-ci-cd-tools)

(GitLab Docs)[https://docs.gitlab.com/ee/ci/docker/using_docker_build.html]
