This project is created to automate application deployment using AWS Pipeline as part of the AWS Certified DevOps Engineer Course.

The local repository is configured to commit changes to both GitHub and AWS CodeCommit repositories. The AWS CodeDeploy uses revisions stored in GitHub to deploy to EC2/On-Premises.

## hello.cpp
This C++ app simply print out "Hello World" and current Date and Time on Linux OS.

## buildspec.yml
AWS CodeBuild agent uses buildspec.yml to run a build.

## appspec.yml
AWS CodeDeploy agent uses appspec.yml (application specification) to manage a deployment on EC2/On-Premise.