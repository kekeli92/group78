# `# DevOps_aws`
## CI/CD pipeline in AWS to deploy a simple website to an EC2 instance using Apache.

### Step1: Create an EC2 Instance and Download the Key Pair.

### Step2: Create Secrets in GitHub for the Repository
    *  EC2_SSH_KEY: This will be your .pem file which you will use to login to the instance
    *  HOST_DNS: Public DNS record of the instance, it will look something like this ec2-xx-xxx-xxx-xxx.us-west-2.compute.amazonaws.com
    *  USERNAME: Will be the username of the EC2 instance, usually ubuntu
    *  TARGET_DIR: Is where you want to deploy your code.

### Step3: Creating your first workflow

### Step4: Testing
