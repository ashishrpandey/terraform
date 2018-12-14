Go to your working directory

    terraform state --help

Pull existing resources in state file

    terraform state pull

List out existing resources

    terraform state list

import state from an existing state file from S3 backend 

    terraform import aws_s3_bucket.tf_code zeke-terraform-bucket

List out new resources compare the output:

    terraform list
