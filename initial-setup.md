
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


### Install Docker 

It is not mandatory
Used to play for Container exercises

      yum install docker -y
      service docker start
      docker --version


Now you can go on to do Terraform Setup
