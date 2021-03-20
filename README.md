# ami assignemnt ci/cd with github action
Use Ubuntu Server 20.04 LTS (HVM), SSD Volume Type as your source image to create custom AMI using packer.

    As of 2/18/21, the current AMI ID is ami-03d315ad33b9d49c4.

All AMI you build should be private. Only you can deploy EC2 instances from it.
All AMI builds should happen in your dev AWS account.
AMI builds should be setup to run in your default VPC. 
The AMI should include everything needed to run your application. 


# Step
```bash
./buildAmi.sh
```
