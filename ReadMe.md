# Amazon Elastic Compute Cloud (Amazon EC2)

## AIM
  Launch Your Amazon EC2 Instance.
  Monitor Your Instance.
  Update Your Security Group and Access the Web Server.
  Resize Your Instance: Instance Type and EBS Volume.
  Explore EC2 Limits.
  Test Stop Protection.
  
  
## Objective:

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

## ALGORITHM

Steps 1:
Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

Steps 2:
Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

Steps 3:
Configure a security group to allow inbound access:
  SSH (Port 22) from your IP address
  HTTP (Port 80) from anywhere (0.0.0.0/0)
This security group acts as a firewall for the instance.

Steps 4:
Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:
```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

Steps 5:
Perform the following operations from the EC2 console:
  Stop the instance
  Start the instance
  Reboot the instance
Observe the state changes of the instance.

Steps 6:

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

Steps 7:
Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.
COMMANDS
Include the commands used in the Experiment.

## OUTPUT
<img width="1600" height="818" alt="WhatsApp Image 2026-05-26 at 9 27 42 PM" src="https://github.com/user-attachments/assets/eeb7d257-2959-44aa-8d2d-652c06710595" />
<img width="1600" height="820" alt="WhatsApp Image 2026-05-26 at 9 28 29 PM" src="https://github.com/user-attachments/assets/a7d9b3b4-df1c-4e22-8744-123d5d2ef69f" />
<img width="1600" height="850" alt="WhatsApp Image 2026-05-26 at 9 29 23 PM" src="https://github.com/user-attachments/assets/7eb5aea9-3149-45cd-b0ff-5d3238cd8874" />
<img width="1600" height="835" alt="WhatsApp Image 2026-05-26 at 9 29 23 PM (2)" src="https://github.com/user-attachments/assets/e49e0ee1-f6a3-4fb1-99a9-99c044e2289e" />
<img width="1600" height="843" alt="WhatsApp Image 2026-05-26 at 9 29 55 PM" src="https://github.com/user-attachments/assets/778a7668-17f6-4b9e-b6a8-088cbb6f5f17" />
<img width="1600" height="843" alt="WhatsApp Image 2026-05-26 at 9 29 55 PM" src="https://github.com/user-attachments/assets/78e28041-73b7-498d-8ead-b42268acc7b1" />
<img width="1600" height="906" alt="WhatsApp Image 2026-05-26 at 9 31 18 PM" src="https://github.com/user-attachments/assets/4252e09f-3d42-4172-a99f-dc327f896671" />

## RESULT

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.

