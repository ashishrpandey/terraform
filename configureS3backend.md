 # Configure S3 backend
 
 AWS Credentials in main.tf may not work
 put it as environment variable
 
 
    export AWS_ACCESS_KEY_ID=""
    export AWS_SECRET_ACCESS_KEY=""
    export AWS_DEFAULT_REGION="ap-south-1"

Once the credencials to AWS are setup
in the main.tf files add and edit following block:

    terraform {
       backend "s3" {
         bucket = "mybucketname"
         key    = "path/to/your/user-defined-terraform-state-file-name"
         region = "us-east-1"
      }
    }

Run terraform init after that

In case of an issue in initialization delete .terraform folder in current directory and run terraform init again
