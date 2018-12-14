
Login your Amazon linux 2 machine [For Other OS the commands may differ]

### Update yum 

      sudo su 
      yum update -y 

### Install git 

      yum install git -y

### Configure AWS CLI 

      aws configure
      AWS Access Key ID [None]: **********
      AWS Secret Access Key [None]: ************
      Default region name [None]: ****
      Default output format [None]:

### Install Terraform 

      wget https://releases.hashicorp.com/terraform/0.11.8/terraform_0.11.8_linux_amd64.zip
      unzip terraform_0.11.8_linux_amd64.zip -d /bin/
      terraform --version

### Install Docker 

It is not mandatory
Used to play for Container exercises

      yum install docker -y
      service docker start
      docker --version
