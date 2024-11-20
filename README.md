 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
   his experiment aims to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.

## ALGORITHM
 Steps 1:
### Login to AWS Management Console:
1.Open the AWS Management Console.

2.Navigate to the S3 service for bucket creation and EC2 for instance setup.

Steps 2:
### Create an S3 Bucket:
1.Go to the S3 service.

2.Click on Create bucket.

3.Provide a unique Bucket Name and select the Region.

4.Configure additional settings as per requirements and click Create bucket.

Steps 3:
### Launch EC2 Instance (Linux):
1.Go to the EC2 service.

2.Click Launch Instance.

3.Select an Amazon Machine Image (AMI), such as Amazon Linux 2.

4.Choose an Instance Type (e.g., t2.micro).

5.Configure instance settings, key pair, and security groups, then Launch the instance.

Steps 4:
### Launch EC2 Instance (Windows):
1.Repeat the EC2 launch steps but select a Windows Server AMI. 2.Complete instance configuration and Launch.

Steps 5:
### Connect to Instances:
1.Linux Instance: Use SSH to connect.

ssh -i "key_pair.pem" ec2-user@<linux_public_dns>
COMMANDS
S3 Bucket Creation
1.AWS CLI Command: aws s3 mb s3:// --region

EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.

EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

## OUTPUT
S3
![image](https://github.com/user-attachments/assets/7a30e0be-7f14-4345-bc6b-c4086537884e)
![image](https://github.com/user-attachments/assets/e102f6a2-ab70-47b7-a449-834ce15690ec)

EC2
![image](https://github.com/user-attachments/assets/95c94cdf-46a1-4d30-9947-8894405cdf81)
![image](https://github.com/user-attachments/assets/98ddad84-a801-4384-aa03-7970dee73cfa)
![image](https://github.com/user-attachments/assets/80a77dad-40e0-497c-a2f6-c7dfa80b305d)


### REG NUMBER:212223040157
### NAME:PRIYANGHA G
 

## RESULT
The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.
 

  


