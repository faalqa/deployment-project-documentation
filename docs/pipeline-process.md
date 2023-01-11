# Pipeline Process

Referring to the scripts in the file [.circleci/config.yml](https://github.com/faalqa/deployment-project-documentation/blob/main/.circleci/config.yml),

The pipeline workflow has two jobs and hold between them:
- Build 
- Hold
- Deploy

After building the project, the pipeline will hold until approving to start deploying

## Environment Setup
setup Node.js, Elastic Beanstalk, and AWS CLI

## Build
- Install Fron-end then back-end dependencies
- Lint front-end then back-end
- Build front-end then back-end

## Deploy
-  Deploy fron-end and back-end

