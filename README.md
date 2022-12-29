
The ultimate goal of practising Continuous Delivery is to enhance the delivery flow. In general, CD:

-	Improve the speed of delivery, and therefore improve the efficiency of an organization.

To understand how CD can be a powerful tool, the organization should be able to understand briefly it works.

# Continuous Delivery 
Continuous Delivery is an engineering approach in which all changes are delivered quickly, safely, and sustainably. It provides an automated high-speed building and testing environment to ensure changes are relevant. This is achieved by ensuring that code is always in a deployable state, even with thousands of changes made daily. In short, CD takes the repetitive tasks in the deployment process and lets people solve problems.

Benefits of implementing CD:
-	**Low risk released**: CD identifies and addresses bugs in the earlier stage before they grow into more significant problems later. 
-	**Improve developer performance**: Teams have more time to focus on creating innovation instead of doing repetitive tasks. Developers are more confident when pushing code into production with an automated, reliable testing process.
-	**Deliver updates faster**: Organizations can deliver updates to customers quickly and frequently.

There are some minimum practices required, and one of them can be mentioned is [Continuous Integration](https://github.com/LeeVo2408/README.md/blob/main/README.md#continuous-integration) 

# Continuous Integration:

>if something takes a lot of time and energy, you should do it more often, forcing you to make it less painful. 

CI is the practice of automating the integration of code changes into a mainline codebase (trunk). Developers merge code changes into a central repository where automated tests are run both before and after the merge, which ensures that the changes do not introduce bugs. 

To successfully implement CI, the minimum requirements are: 

-	**Trunk-based development**: developers divide their work into small branches and merge that work into a trunk frequently.
-	**Continually**: automated testing process
-	**Visability**: the status of the work should be visible to the team.

# Open- source CI/CD Tools
######1 . Jenkins
One of the leading CI/CD tool on the market. Jenkins is a cross-platform, java-based tool that mainly supports Ci operation. In addition, Jenkins can be extended via plugins, which integrate other development lifecycle operations, such as build, document, deploy, and much more.

The benefits of Jenkins are:
-	High security
-	Easy to set up 
-	It can run on all major platforms
-	Huge variety of plugins  

Disadvantages: 
-	Difficult in managing plugin
-	It does not allow sever-to-server federation 

######2.	GitLab 
Gitlab is a collection of tools for managing various areas of the software development cycle. The core product is a web-based Git repository manager with tools for issues tracking, analytics and wiki.

Developers have the option to start builds, launch tests, and deploy code when push or commit code on Gitlab 

Advantages:
-	Simple Configuration 
-	High security
-	Automated pipeline 
-	Allow self-hosting on any plan 
-	Supports Docker
Disadvantages:
-	The interface might be slower than other platforms.
-	Common problems with repositories.
