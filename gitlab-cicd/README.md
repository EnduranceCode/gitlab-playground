# GitLab CI/CD: Pipelines, CI/CD and DevOps for Beginners

This [folder](./) contains the code written while taking the course
[GitLab CI/CD: Pipelines, CI/CD and DevOps for Beginners](https://www.udemy.com/course/gitlab-ci-pipelines-ci-cd-and-devops-for-beginners/)
which is presented by [Valentim Despa](https://www.linkedin.com/in/vdespa/).

## Table of Contents

1. [Course Content & Progress](#course-content--progress)
2. [Folder Structure](#folder-structure)

## Course Content & Progress

1. Section 1: Introduction to GitLab CI/CD. Fundamental CI/CD concepts & DevOps
    - [x] Introduction to the GitLab CI/CD course
    - [x] What is GitLab CI/CD?
    - [x] GitLab.com account registration
    - [x] Verifying your GitLab account
    - [x] What is a pipeline?
    - [x] Your first pipeline
    - [x] Help! My GitLab CI pipeline is not running.
    - [x] Adding pipeline stages
    - [x] Quiz 1: Fundamental GitLab and CI/CD concepts
    - [x] GitLab CI/CD architecture
    - [x] GitLab CI/CD architecture (Part 2)
    - [x] How much does GitLab cost?
    - [x] Quiz 2: GitLab architecture quiz
    - [x] What is a Linux shell?
    - [x] Writing comments in a GitLab pipeline
    - [x] Manually stopping a pipeline
    - [x] Brief introduction to YAML
    - [x] Safeguarding CI pipelines with effective tests
    - [x] Why do jobs and pipelines fail (exit codes)
    - [x] Important skills you need to acquire
    - [x] What is DevOps?
    - [x] Role 1: GitLab CI/CD and DevOps fundamentals
    - [x] Conclusion
2. Section 2: Continuous Integration (CI) with GitLab (Stages, Test, Reports, Merge Requests)
    - [x] Introduction to Continuous Integration (CI)
    - [x] Forking a Git repository
    - [x] Running the project locally (optional)
    - [x] Using Docker as a build environment
    - [x] Choosing an appropriate Docker image
    - [x] Lightweight Docker images (alpine, slim)
    - [x] Building the project using GitLab
    - [x] Quiz 3: Docker as a build environment in GitLab CI/CD
    - [x] Assignment: Publishing build artifacts
    - [x] Assignment: Publishing build artifacts
    - [x] Revisiting the GitLab CI/CD architecture
    - [x] Quiz 4: GitLab architecture quiz
    - [x] Assignment: Adding a test stage
    - [x] Quiz 5: Assignment - Adding a test stage - Step-by-step instructions
    - [x] Assignment: Adding a test stage - Solution
    - [x] Running unit tests
    - [x] Running jobs in parallel
    - [x] Default pipeline stages (.pre, build, test, deploy .post)
    - [x] Publishing a JUnit test report
    - [x] Testing the tests (ensure that the tests fail!)
    - [x] Quiz 6: The role of unit tests in CI pipelines
    - [x] How to integrate changes?
    - [x] Configuring Merge Requests
    - [x] Making changes through a Merge Request
    - [x] Code review and merging changes
    - [x] Quiz 7: Merge requests
    - [x] Configuring a code linter
    - [x] How to structure a pipeline?
    - [x] Quiz 8: Understanding code linters
    - [x] Simplifying the pipeline
    - [ ] Section recap
3. Section 3: Continuous Deployment (CD) with GitLab
    - [ ] Section Overview
    - [ ] Manual deployment
    - [ ] Installing CLI tools
    - [ ] [ACTION REQUIRED] Important update regarding Netlify CLI
    - [ ] Storing project configuration in environment variables
    - [ ] Managing secrets
    - [ ] Best practices for handling credentials
    - [ ] Quiz 9: Managing variables and secrets in GitLab
    - [ ] Deploying to production
    - [ ] Smoke tests
    - [ ] Quiz 10: Deployments with GitLab
    - [ ] Conditional job execution with rules:
    - [ ] Scripts: before_script and after_script
    - [ ] Deployment Strategies: Non-production environments
    - [ ] Deploying to the staging environment
    - [ ] Manual approval step before deploying to production
    - [ ] Continuous Delivery and Continuous Deployment
    - [ ] Creating review environments
    - [ ] Merge request pipeline vs Branch pipeline
    - [ ] Parsing CLI response data (w/ jq JSON parser)
    - [ ] Defining dynamic environments
    - [ ] Defining static environments
    - [ ] Scoping variables to a specific environment
    - [ ] Quiz 11: CI/CD & Deployment environments
    - [ ] Project simulation using merge requests
    - [ ] End-to-end tests with wright (E2E tests)
    - [ ] Passing data between jobs with environment variables
    - [ ] Assignment: Publishing the E2E JUnit report
    - [ ] Quiz 12: Publishing the E2E JUnit report - Step by step instructions
    - [ ] Assignment: Publishing the E2E JUnit report - Solution
    - [ ] Publishing an HTML report
    - [ ] Quiz 13: End-to-End Testing in GitLab CI/CD
    - [ ] Setting a build version
    - [ ] A critical analysis of the pipeline
    - [ ] Why CI/CD really matters
    - [ ] Quiz 14: CI/CD recap
    - [ ] Conclusion & coffee break
4. Section 4: Introduction to Docker for DevOps
    - [ ] Section overview
    - [ ] Creating a Dockerfile
    - [ ] Running Docker CLI commands in GitLab
    - [ ] Building a Docker image
    - [ ] GitLab container registry
    - [ ] Pushing an image to the GitLab container registry
    - [ ] Using a custom Docker image in the pipeline
    - [ ] Create a scheduled pipeline
    - [ ] Microsoft Artifact Registry
5. Section 5: Continous Deployment to AWS (AWS CLI, IAM, S3) with GitLab
    - [ ] Introduction to Amazon Web Services (AWS)
    - [ ] Amazon S3 (object storage)
    - [ ] AWS CLI
    - [ ] Managing AWS services with AWS CLI
    - [ ] Identity management with AWS IAM
    - [ ] Managing AWS credentials in GitLab - Assignment
    - [ ] Managing AWS credentials in GitLab - Assignment Solution
    - [ ] Uploading a file to S3
    - [ ] Hosting a website on S3
    - [ ] Syncing files to S3
    - [ ] Conclusion
6. Section 6: Deploying over SSH to a remote server with GitLab (SSH, SCP, rsync)
    - [ ] Amazon Elastic Compute Cloud (EC2)
    - [ ] Creating an Ngnix web server
    - [ ] Testing the connection with netcat (nc)
    - [ ] 25 - Testing the SSH connection from GitLab
    - [ ] Storing the SSH private key in GitLab
    - [ ] Configuring the SSH connection
    - [ ] Verifying the SSH host keys
    - [ ] Running commands over SSH
    - [ ] Uploading files using SCP
    - [ ] Uploading files using rsync
    - [ ] Running a deployment script
    - [ ] Conclusion
7. Section 7: Continuous Deployments to Amazon Elastic Container Service (ECS, ECR, IAM)
    - [ ] Introduction to Amazon Elastic Container Service (Amazon ECS)
    - [ ] ECS Infrastructure / Launch modes (Fargate vs EC2)
    - [ ] Creating a cluster in ECS
    - [ ] Creating a task definition
    - [ ] Creating a deployment on ECS
    - [ ] Updating the task definition using AWS CLI
    - [ ] Updating the service using AWS CLI
    - [ ] wait command
    - [ ] Steps needed to deploy an application to ECS
    - [ ] Creating the Dockerfile
    - [ ] Building the Docker image
    - [ ] Amazon ECR - Docker container registry
    - [ ] Using an ECR Docker image in the task definition
    - [ ] Section summary & conclusion
8. Section 8: Advanced GitLab CI/CD features
    - [ ] Section overview
    - [ ] Retrying failed jobs automatically (retry keyword)
    - [ ] Allowing failures (allow_failure keyword)
    - [ ] YAML anchors and aliases
    - [ ] Job templates with YAML anchors and aliases (practical example)
    - [ ] Reusing configuration with extends:
    - [ ] Import YAML configuration from other files (includes keyword)
    - [ ] CI/CD Components & Catalog
    - [ ] Writing multi-line scripts
    - [ ] Running a server / background process within a job
    - [ ] GitLab Pages
    - [ ] Choosing the GitLab Runner using tags
9. Section 9: Pipeline performance optimizations
    - [ ] Skip cloning the Git repository (GIT_STRATEGY)
    - [ ] Disabling artifact download from previous stages (dependencies keyword)
    - [ ] Stageless pipelines: running jobs out of order (needs keyword)
    - [ ] Using the needs keyword with artifacts
    - [ ] Caches
    - [ ] Caches vs Artifacts
    - [ ] Dynamic cache keys (cache configuration)
    - [ ] Cache key from file (cache configuration)
    - [ ] Disabling cache (cache configuration)
    - [ ] Cache policy (cache configuration)
    - [ ] Dynamic cache policy (cache configuration)
    - [ ] Troubleshooting the cache configuration
10. Section 10: Specific topics/User topics
    - [ ] Ask the instructor
11. Section 11: Conclusion
    - [ ] Not the end
    - [ ] Bonus lecture

## Folder Structure

### video-004

The folder [`video-004`](./video-004) contains the pipeline that started to be developed with the 4th video
of this course (*Verifying your GitLab account*).

### video-006

The folder [`video-006`](./video-006) contains the pipeline that started to be developed with the 6th video
of this course (*Your first pipeline*).

### learn-gitlab-app

The folder [`learn-gitlab-app`](./learn-gitlab-app) contains the cloned
from the [repository](https://gitlab.com/gitlab-course-public/learn-gitlab-app) as required for the 22nd video
of this course (*Forking a Git repository*).
