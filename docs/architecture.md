# Udagram Infrastructure

![app archtiecture](./Architecture.png)

## RDS

The Postgres Database.

URI: `postgres://postgres:postgres@udagram.copc0tziqsib.us-east-1.rds.amazonaws.com/udagram`

## Elastic Beanstalk

Application Development Environment for Node.js and back-end.

Environment URI: `http://udagram-api.eba-pmvdvdm4.us-east-1.elasticbeanstalk.com/`

## S3 Buckets

### Front-end Bucket

URL: `http://udagram-frontend112.s3-website-us-east-1.amazonaws.com/`

URI: `s3://udagram-frontend112`

### Store Bucket

This bucket is for  image storing in the application.

URI: `s3://*******` (private)
