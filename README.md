# Ex 4 Deployment and configuration of a Private Cloud in AWS

## Aim:
To set up of a Private Cloud in AWS.

## Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:

### Plan Your VPC:
● Determine your needs:

### Define your use case, including application requirements, security needs, and compliance standards.

● Plan IP address ranges:

### Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:

### Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.

● Plan internet connectivity:

### Determine if you need public internet access and how to configure it.

● Define security:

### Plan your security groups, network ACLs, and access controls to ensure a secure environment.

### Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

### Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

### Managing and Monitoring:

• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:

### Snapshot 1: Create VPC image

<img width="1038" height="617" alt="image" src="https://github.com/user-attachments/assets/db9bf0c1-1076-49d6-bcc3-ddf3ed86d1b7" />

### Snapshot 2: Configuring Subnets

<img width="1041" height="533" alt="image" src="https://github.com/user-attachments/assets/7fa703f1-878a-4ebd-9b5b-b5c31f8699fd" />

### Snapshot 3: Configure Subnets

<img width="1203" height="689" alt="image" src="https://github.com/user-attachments/assets/ad1e29fb-e34a-4bef-a0f0-33b2ce5bac57" />

### Snapshot 4: Setting Internet gateway

<img width="1134" height="592" alt="image" src="https://github.com/user-attachments/assets/bc05b1b3-c7a2-4169-907e-508368335c4c" />

### Snapshot 5: Setting Internet gateway

<img width="1200" height="711" alt="image" src="https://github.com/user-attachments/assets/21d4b978-6d7a-4bce-93a0-dfc8c65f9b5d" />

### Snapshot 6: Setting Internet gateway

<img width="1186" height="604" alt="image" src="https://github.com/user-attachments/assets/bc078868-de92-490a-9d74-3de5d51ce8ef" />

### Snapshot 7: Creating route table

<img width="1171" height="636" alt="image" src="https://github.com/user-attachments/assets/59a7d32c-b556-409b-be53-a4e3c1896d4b" />

### Snapshot 8: Configuring route table

<img width="1156" height="704" alt="image" src="https://github.com/user-attachments/assets/5c05a8a8-5dcd-47da-9073-62591b07ba11" />

### Snapshot 9: Editing routes

<img width="1191" height="602" alt="image" src="https://github.com/user-attachments/assets/f7e70d68-bdd1-40df-90fe-2dec7142074d" />

### Snapshot 10: Creating route table

<img width="1159" height="584" alt="image" src="https://github.com/user-attachments/assets/c0d43eca-dd8c-4cad-a911-b87de33b617d" />

## Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
