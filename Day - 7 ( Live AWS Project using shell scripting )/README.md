
# LIVE AWS project using shell Scripting


## Write a script to report the usage of AWS in your project ??


AWS cli Install :

Connect to EC2 Instances :

- bash
- aws configure -> Access key -> default region name -> json

###

### File name

vim aws_resource_tracker

#!/bin/bash

Author : Rishabh

Date : 5 March


📌 This script will report the AWS resource usage :

AWS S3

AWS EC2

AWS Lambda

AWS IAM Users


###

###  List S3 buckets

echo "Print list of s3 bucktes "

aws s3 ls

###

### List EC2 Instances

echo "Print list of ec2 instances "

aws ec2 describe-instances

###

### list Lambda

echo "Print list of lambda functions "

aws lambda list-function

###

### list IAM Users

echo "Print list of IAM Users bucktes "

aws IAM list-users




