# Description

This repo contains a reference of useful CloudFormation templates for common use cases

## S3

- [S3-Assume-Role.yaml](src/S3-Assume-Role.yaml): allows an external application to assume a role that can read a S3 bucket

## SNS

- [SNS-invoke-SQS.yaml](src/SNS-invoke-SQS.yaml): allows a SQS queue to subscribe to a SNS topic, useful for pub-sub fan-out
