# Prerequisites
ubuntu or whatever linux distro

aws-cli

aws-sdk

ansible

# Preparing a Local Environment
# For ubuntu

> sudo apt update

> sudo apt install python3-pip

> pip3 install awscli  

# https://docs.aws.amazon.com/cli/latest/userguide/install-linux.html

> pip3 install boto boto3 botocore

> pip3 install ansible

# configure aws credentials with aws-cli
> aws configure

> cat .aws/credentials

# You can get keys from the Your Security Credentials page in the AWS Management 
AccessKeyId: AKIALNZTQW6H3EFBRLHQ

SecretAccessKey: f26B8touguUBELGpdyCyc9o0ZDzP2MEUWNC0JNwA

# Testing your aws credentials is working or not

> aws sts get-caller-identity

# to use aws credentials in ansible use environment variables
# modify your ~/.bashrc or ~/.bash_profile

export AWS_ACCESS_KEY_ID='your access key id'

export AWS_SECRET_ACCESS_KEY='your secret access key'

export AWS_REGION='your region'























