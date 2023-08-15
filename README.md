# Introduction to AWS EC2

This summary is for [this video](https://www.youtube.com/watch?v=YRCZ1jt36uo&t=635s)


 ### Session Introduction 
 The session begins with a warm welcome to all attendees, followed by a brief introduction to AWS EC2. The speaker also highlights some essential points, such as attendees being muted by default during the session and the availability of a question and answer session at the end of the presentation. 
 ### AWS EC2 Overview and Architecture 
 This key point covers the global infrastructure of AWS, including data centers and availability zones. It explains the concept of EC2 instances as virtual machines running in the cloud, providing resizable compute capacity. The architecture of an EC2 instance is briefly explained, emphasizing the role of security groups and key pairs. Additionally, the benefits of using AWS EC2 under the free tier are discussed, providing insights into cost-effective cloud computing for beginners. 
 ### Free Tier EC2 Instances 
 In the free tier AWS account, you are allowed to use certain EC2 instances without incurring charges. The T2 Micro instance is commonly used by beginners and offers 1GB RAM and one virtual CPU. There's also the T3 Micro and T4g Small instances available until 31st December. Remember, not all instances may be available in all regions. 
 ### Key Components for Launching EC2 Instance 
 Before launching an EC2 instance, you need to understand key components. An Amazon Machine Image (AMI) is a template with software configuration information, similar to an OS CD. Instance type determines the hardware, like CPU, memory, and storage. Security groups act as virtual firewalls, defining rules for access to your EC2 instance. Lastly, you'll require a key pair for authentication to connect to the instance. 
 ### Selecting PPK or PEM-based File 
 When setting up an EC2 instance, you have the option to choose between a PPK file for use with Putty or a PEM-based file for other SSH clients. The speaker prefers the PEM-based key as it is more user-friendly and versatile for connecting. 
 ### Defining Security Group for EC2 
 The second requirement for setting up an EC2 instance is to define a security group. The speaker demonstrates creating a new security group that allows SSH and RDP connections. They emphasize the importance of configuring inbound rules carefully to restrict access and avoid security risks. 
 ### Connecting to a Linux-based EC2 Instance 
 To connect to a Linux-based EC2 instance, you need to use an SSH client like MobaXterm. Make sure to have the public IP or public DNS of your EC2 instance and the default username 'ec2-user' for Amazon Linux or 'ubuntu' for Ubuntu-based AMIs. Also, select the appropriate key pair for authentication, and ensure that the security group allows SSH access from your IP address. 
 ### Connecting to a Windows-based EC2 Instance 
 For connecting to a Windows-based EC2 instance, you should use Remote Desktop Protocol (RDP). First, get the public IP of the instance and the default username 'Administrator.' Then, retrieve the Windows administrator password using your key pair. Download the RDP file, enter the password, and you'll be able to access your Windows EC2 instance with GUI capabilities. 
