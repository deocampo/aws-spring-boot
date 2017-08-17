## Initial Setup

### Base Project 

The Spring boot codebase comes from the barebones spring-boot sample downloaded from the [Spring Github Repo](https://github.com/spring-guides/gs-spring-boot). This contains the Main controller mapped to ["/"]().

### Deployed

Project is deployed into Amazon Web Services. It may still be running at the following [on my AWS Account](). The site is not up for long since I am using a free account.

## Extensions

### 1. Akka

Added Akka code executed from the following [instructional site]([Extending springboot to apply Akka](http://kimrudolph.de/blog/spring-boot-meets-akka). This contains the tensorflow controller that is mapped to ["/"]().


## Integration

The following instructions are the steps to get this github project integrated to aws:

### [AWS Github Tutorial](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github.html)

These are the major steps :

- [Prerequisites - In progress](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-prerequisites.html)()
- [Step 1: Set Up a GitHub Account - Done](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-create-github-account.html)
- [Step 2: Create a GitHub Repository - Done](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github.html)
- [Step 3: Upload a Sample Application to Your GitHub Repository - Done using SpringBoot App](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-upload-sample-revision.html)
- [Step 4: Provision an Instance](http://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-provision-instance.html)
- [Step 5: Create an Application and Deployment Group]()
- [Step 6: Deploy the Application to the Instance]()
- [Step 7: Monitor and Verify the Deployment]()
- [Step 8: Clean Up]()

