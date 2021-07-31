# Hosting a full-stack application with AWS and CircleCI
### Hosting link: 
#### http://udagram-hosting.s3-website.us-east-2.amazonaws.com/home

This Udagram application was provided by Udacity. The goal of this final project was to connect Udagram to Amazon Web Services. S3 (udagram-frontend) was used for hosting and posts; RDS was used for the PostgreSQL database; Elastic Beanstalk was used for the API (udagram-backend). The full application in all its glory can be visited via the link at the top. 

The other aim of this project was to learn to create a pipeline with CircleCI, so any time udagram-master project code is altered then the updated product is immediately available for users. This means that users get the latest and greatest features of Udagram every time it is updated.

[![CurtisGrayeBabin](https://circleci.com/gh/CurtisGrayeBabin/udagram-udacity.svg?style=svg)](https://app.circleci.com/pipelines/github/CurtisGrayeBabin/udagram-udacity/8/workflows/b05adec4-ec01-4533-a730-3ade7d591c46/jobs/11)