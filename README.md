# Ex 4: Deployment and Configuration of a Private Cloud in AWS

## Aim:
To set up a Private Cloud in AWS.

## Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security.

Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:

## 1. Plan Your VPC:
- **Determine your needs:**
  Define your use case, including application requirements, security needs, and compliance standards.
- **Plan IP address ranges:**
  Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
- **Select Availability Zones:**
  Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.
- **Plan internet connectivity:**
  Determine if you need public internet access and how to configure it.
- **Define security:**
  Plan your security groups, network ACLs, and access controls to ensure a secure environment.

## 2. Create Your VPC:
- **Sign in to AWS Management Console:** Access the VPC console and navigate to the VPC dashboard.
- **Choose "Create VPC":** Initiate the VPC creation process.
- **Configure VPC details:** Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.
- **Create subnets:** Define subnets within your VPC to isolate different parts of your network.
- **Create route tables:** Specify how traffic is routed within and outside the VPC.
- **Create security groups:** Define access control rules for your resources.

## 3. Deploying Resources:
- **Launch EC2 instances:** Create and launch virtual machines within your VPC.
- **Set up RDS instances:** Deploy databases for your applications.
- **Configure networking:** Connect your resources to the appropriate subnets, security groups, and route tables.
- **Deploy other AWS services:** Integrate other services like S3 for storage and Lambda for serverless computing.

## 4. Managing and Monitoring:
- **Use AWS CloudWatch:** Monitor your VPC and resources for performance and health.
- **Configure logging and auditing:** Track access and activity within your VPC for security and compliance.
- **Implement security best practices:** Regularly review and update your security configuration.
- **Scale and adjust as needed:** Adjust your VPC infrastructure to meet changing demands.

## Snapshots:
<p align="center">
  <img src="https://github.com/user-attachments/assets/ed1da414-cd66-4843-9931-f1539d0ee295" width="600" alt="Create VPC" />
</p>
<p align="center"><strong>Snapshot 1: Create VPC</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d3224c1-2935-4b8f-9f87-6de6cbc34b2d" width="600" alt="Configuring Subnets" />
</p>
<p align="center"><strong>Snapshot 2: Configuring Subnets</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3bdc9f2e-30d7-4c40-b5ef-5e26b8566298" width="600" alt="Configure Subnets" />
</p>
<p align="center"><strong>Snapshot 3: Configure Subnets</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/49266fc8-045d-43ab-bb43-da9db1d154bf" width="600" alt="Setting Internet Gateway" />
</p>
<p align="center"><strong>Snapshot 4: Setting Internet Gateway</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9c922b5e-bd69-48ad-a5b6-7eda3fc23737" width="600" alt="Setting Internet Gateway" />
</p>
<p align="center"><strong>Snapshot 5: Setting Internet Gateway</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/df93ed96-a34f-4c96-91ce-330bf2571a81" width="600" alt="Setting Internet Gateway" />
</p>
<p align="center"><strong>Snapshot 6: Setting Internet Gateway</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/84ad70d7-ec98-4fc5-a809-51eddfa852b2" width="600" alt="Creating Route Table" />
</p>
<p align="center"><strong>Snapshot 7: Creating Route Table</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/94ef6505-dc46-4eea-8cb5-a699e990931c" width="600" alt="Configuring Route Table" />
</p>
<p align="center"><strong>Snapshot 8: Configuring Route Table</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/18bde05d-9147-4218-9959-c85706c9a2a5" width="600" alt="Editing Routes" />
</p>
<p align="center"><strong>Snapshot 9: Editing Routes</strong></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/974222ab-46dd-4031-89f6-25e52a502815" width="600" alt="Creating Route Table" />
</p>
<p align="center"><strong>Snapshot 10: Creating Route Table</strong></p>

## Result:
Thus, a private cloud on AWS using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
