# AWS_Capstone_Project_1
Deploying a Multi-Tier Website Using AWS EC2 and RDS
📖 Project Description
This project involves migrating a company's web application to AWS Cloud, ensuring high availability, scalability, and managed database service. The website is built on PHP, and the database is MySQL. To meet the company's needs, we used EC2, Auto Scaling Groups, and RDS services in AWS.

🛠️ Technologies Used
AWS EC2 (Elastic Compute Cloud)

AWS RDS (Relational Database Service)

AWS Auto Scaling Group

Amazon VPC (for networking)

PHP (for the web application)

MySQL (for the database)

Security Groups

IAM Roles

🚀 Project Steps
Launch EC2 Instances

Created Amazon Linux 2 AMI instances for hosting the PHP website.

Installed Apache, PHP, and necessary dependencies.

Enable Auto Scaling

Set up an Auto Scaling Group (ASG) with a minimum of 2 instances to maintain high availability.

Configured Launch Template and Target Group.

Set Up RDS Instance

Created a MySQL RDS instance with:

Database Name: intel

Master Username: admin

Password: intel123

Configure Database

Created a table named data inside the intel database.

Adjusted security groups to allow inbound traffic from the EC2 instances.

Connect Website to RDS

Updated the website configuration to point to the RDS endpoint instead of localhost.

Verified database connectivity from PHP website.

Networking and Security

Configured EC2 Security Group to allow all traffic (for testing).

Allowed EC2 security group access to RDS (port 3306).

Testing

Accessed the website using the EC2 public IP / Load Balancer DNS.

Performed insert/retrieve operations from the RDS database through the website.
📈 Outcome
Achieved high availability with Auto Scaling.

Separated compute and database layers.

Successfully migrated a legacy website to a scalable AWS cloud environment.
