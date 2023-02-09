[![Board Status](https://dev.azure.com/htunn/f1a8c442-29ce-4705-a287-cb938d80e40e/edb43178-2506-44c1-a155-6b1426179b13/_apis/work/boardbadge/9fc4b2ec-15f6-49ed-86d0-651bb310a0ca)](https://dev.azure.com/htunn/f1a8c442-29ce-4705-a287-cb938d80e40e/_boards/board/t/edb43178-2506-44c1-a155-6b1426179b13/Microsoft.RequirementCategory)
# Prerequisites
**ubuntu or whatever linux distro**

1. aws-cli
2. aws-sdk
3. ansible

## Preparing a Local Environment
## For ubuntu

* sudo apt update
* sudo apt install python3-pip
* pip3 install awscli
* pip3 install boto boto3 botocore
* pip3 install ansible

[AWS CLI Links](https://docs.aws.amazon.com/cli/latest/userguide/install-linux.html)

## configure aws credentials with aws-cli

* aws configure
* cat .aws/credentials

## You can get keys from the Your Security Credentials page in the AWS Management 
> AccessKeyId: example_key

> SecretAccessKey: example_secret_key

## Testing your aws credentials is working or not

> aws sts get-caller-identity

#### to use aws credentials in ansible use environment variables
#### modify your bash_rc or bash_profile

> export AWS_ACCESS_KEY_ID='your access key id'


> export AWS_SECRET_ACCESS_KEY='your secret access key'

>  export AWS_REGION='your region'


![AWS and Ansible](https://miro.medium.com/max/690/1*Fv41i7neEp1AaP8RrpJOig.png)




















