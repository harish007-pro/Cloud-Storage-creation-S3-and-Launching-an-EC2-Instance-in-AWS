# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS

## NAME: G HARISH 
## REG.NO: 212224110020
## Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
## Procedure
## a)	Steps to Create a first S3 Bucket:
## Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
## Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
## Step 3: Create Bucket
Click the Create bucket button.
## Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
## Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
## Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
## Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
## Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
## Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
## Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
## b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

## c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

## d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.

## Snap Shot 1: Simple Storage Service (S3):
<img width="1147" height="512" alt="Screenshot 2026-11-04 085947" src="https://github.com/user-attachments/assets/368a33ed-29f8-4ae8-8c88-c30cbc012c80" />


## Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance


<img width="1155" height="485" alt="Screenshot 2026-11-04 085959" src="https://github.com/user-attachments/assets/82931842-a9aa-458a-90d0-3923a5945345" />

<img width="1156" height="508" alt="Screenshot 2026-11-04 090219" src="https://github.com/user-attachments/assets/5d30b58a-9c4f-49bf-902c-84af613561ae" />


<img width="1152" height="502" alt="Screenshot 2026-11-04 090229" src="https://github.com/user-attachments/assets/db2b6615-4e43-46e1-bdef-ba30fa22202f" />

<img width="1152" height="507" alt="Screenshot 2026-11-04 090246" src="https://github.com/user-attachments/assets/f26c66e7-e719-4d18-8b0f-a1fd4eef0b86" />

<img width="1152" height="502" alt="Screenshot 2026-11-04 090303" src="https://github.com/user-attachments/assets/f38ae0ea-551f-4870-bc11-eccf6990c785" />

<img width="1158" height="505" alt="Screenshot 2026-11-04 090317" src="https://github.com/user-attachments/assets/2bb07b95-be98-429b-8ac3-243080516300" />

<img width="1160" height="506" alt="Screenshot 2026-11-04 090326" src="https://github.com/user-attachments/assets/24b35a6f-3085-4df5-b6f9-fd236994fe6e" />


<img width="1148" height="502" alt="Screenshot 2026-11-04 090340" src="https://github.com/user-attachments/assets/3c359363-edbf-4af8-9298-75340ee84b79" />

<img width="1155" height="508" alt="Screenshot 2026-11-04 090403" src="https://github.com/user-attachments/assets/701e018d-c948-41c0-9757-59db09b93dd6" />

<img width="1156" height="507" alt="Screenshot 2026-11-04 090416" src="https://github.com/user-attachments/assets/79cb7423-99ec-470c-8197-725788a8e9d1" />


<img width="1151" height="505" alt="Screenshot 2026-11-04 090427" src="https://github.com/user-attachments/assets/78c333bd-b8d4-43f9-9753-8f16f22bf312" />

<img width="1153" height="507" alt="Screenshot 2026-11-04 090438" src="https://github.com/user-attachments/assets/0f82711c-9b44-484e-8729-75134808fed5" />


<img width="1152" height="507" alt="Screenshot 2026-11-04 090508" src="https://github.com/user-attachments/assets/344cdf6d-69df-408b-a8d8-ca4cbb7d7a76" />

<img width="1155" height="512" alt="Screenshot 2026-11-04 090519" src="https://github.com/user-attachments/assets/74c18d4e-370b-412b-8d79-5fa0b58c32b6" />







## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
