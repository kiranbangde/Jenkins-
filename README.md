# Jenkins -

## What is the latest version of Jenkins ?

The latest Jenkins version is 2.463, which was released weekly on June 18, 2024. This version requires Java 17 or newer.

## What is continuous interation and continuous delivery ?

### CONTINUOUS INTEGRATION --

CI is one of the most popular application development practices in recent times. Developers integrate bug fix,new feature development, or innovative functionality in code repository. The CI tool verifies the integration process with an automated build and automated test execution to detect issues with the current source of an application, and provide quick feedback.

Continuous integration is a DevOps software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run.
Continuous integration most often refers to the build or integration stage of the software release process and entails both an automation component (e.g. a CI or build service) and a cultural component 
(e.g. learning to integrate frequently). The key goals of continuous integration are to find and address bugs quicker, improve software quality, and reduce the time it takes to validate and 
release new software updates .

## Features of continuous integration --

1. Fast delivery

### Continuous integration = continous build + continuous test

## Tools other than jenkins used in market --

## THIS all are paid tools 

1. BAmboo (Paid) (enterprise version)
2. Travis CI (Paid)
3. Buildbot (Paid)
4. Jenkins is a open source tool

## What is jenkins why it is most popular ?

Jenkins is an open source application written in Java. It is one of the most popular continuous integration (CI) tools used to build and test different kinds of projects.

Jenkins is a simple, extensible, and user-friendly open source tool that provides CI services for application development.

The concept of plugins makes Jenkins more attractive, easy to learn, and easy to use. There are various categories of plugins available such as Source code management,
Slave launchers and controllers, Build triggers, Build tools, Build notifies, Build reports, other post-build actions.

### Jenkins is a continious integration tool .

jenkins was originally devlop by sun microsystem.

1. It have a Strong Community support . 
2. Support  lots of plugins .
3. It automate the software devlopment life cycle .
4. It can run on any platform without any compatibility issues.
5. for jenkins java must be install in system because jenkin is written in java .
6. Because of CI bugs are reported fastly and can be retified fast , so that the entired software devlopment get fast.

## Distributed Architecture of Jenkins . ( Master and Slaves architecture )

suppose some application required window platform and some require the linux platform for that we required the master and slaves architectures.

Jenkins master will distribute its workload to the slaves. 

Jenkins slaves are generally required to provide the desired environment. It works on basis of requests received fron jenkins master. 

## Workflow of jenkins 

1. Developer commits chnages to the source code .
2. Continous integration server pulls that code trigger a build.
3. build application is then deployed on the testing server for testing.
4. After testing the application , it is then deployed to the production server
5. The concerned team are constantly notified about the build and test results.


## What is artifactory ?

It is a repository where our final code is stored means ready to use code is store.  Used for future used . 

## What are plugins ?

Plugins are small  libraries that add new ability to jenkins and can provide integartion points to other tools .
Plugins in Jenkins are add-ons that extend the functionality of the Jenkins automation serve.
Plugins help customize Jenkins to meet the needs of a user or organization. They can integrate with build tools, cloud providers, and analysis tools.

## what is pipeline ?

data pipeline, is a set of data processing elements connected in series, where the output of one element is the input of the next one.

![image](https://github.com/user-attachments/assets/efc139fe-a03a-491b-bf67-43afdb7c9f8a)

## Where is our jenkins password store ?

/var/lib/jenkins/secrets/initialadminpassword

## What is job in jenkins ?

A job in Jenkins is a set of tasks or processes that are defined and executed automatically to perform work. Jobs can include tasks like compiling source code, running tests, or deploying applications.

## what is RBAC (ROLE BASE ACCESS CONTROL)?

## What is trigger in jenkins ?

A trigger in Jenkins is a feature that automates builds and deployments based on specific events or conditions. Triggers can be used to: 
Initiate builds when changes are made to a repository 
Trigger builds on a schedule

Some popular triggers in Jenkins include: Git webhook, Poll SCM, Scheduled job, Remote triggers, and Build After other project are build.

## WHAT IS WORKSPACE IN JENKINS ?



