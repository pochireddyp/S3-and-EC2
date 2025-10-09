# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# NAME :pochireddy
# REG NO : 212223240115

# Aim:

To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure 

**a) Steps to Create a first S3 Bucket:**

Step 1: Sign in to the AWS Management Console 

   Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service 

   In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket 

  Click the Create bucket button. 

Step 4: Configure Bucket Settings 

   • Bucket name: Choose a globally unique name. 

   • AWS Region: Select the region where you want to store your data. 

Step 5: Object Ownership 

   Choose between: 

  • ACLs disabled (recommended) – Bucket owner has full control. 

  • ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings 

   By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) 

   Choose whether to enable versioning for objects in the bucket. 

Step 8: Encryption (optional) 

   Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) 

   Add tags, configure logging, etc. 

Step 10: Create the Bucket 

   Click Create bucket at the bottom of the page. 

**b)  Steps to launch an EC2 Instance**

1. Go to the EC2 Dashboard in AWS Console.

3. Click on “Launch Instance”. 

4. Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux). 

5. Select an instance type (e.g., t2.micro for Free Tier). 

6. Create or choose a key pair for SSH access. 

7. Configure network settings (use default VPC/subnet). 

8. Configure storage (default root volume is fine). 

9. Review the settings and click “Launch Instance”. 

10. Wait for the instance to enter the running state. 


**c)  Connect to Your Instance**

   • Linux: Use SSH command with your .pem key. 

   • Windows: Use RDP with decrypted admin password. 


Steps to Clean Up (Terminate the Instance) 

   1. Go to EC2 Instances. 

   2. Select your instance → Instance State → Terminate. 


# Snap Shots:
## _Snapshot 1: Simple Storage Service (S3)_
<img width="1919" height="853" alt="Screenshot 2025-09-17 105407" src="https://github.com/user-attachments/assets/a77e7e8e-d4f7-4ff6-bfd5-adf7a2b0f269" />

                                                       


## _Snapshot 2:  EC2 (Elastic Compute Cloud) – Instance
<img width="1919" height="907" alt="Screenshot 2025-09-17 110416" src="https://github.com/user-attachments/assets/5dc71130-2dbb-4a00-8047-751746cd519e" />

                                                      


# Result: 

Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS 


