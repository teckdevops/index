---
layout: post
title: AWS EC2 - Management Console
---

A Blog post to explain the basic concepts of AWS EC2(Amazon Web Service Elastic Compute Cloud) service. 

AWS EC2 is a service that basically provides scalable compute capacity on an on-demand, pay-per-use basis to its end users. EC2 is simply based on server virtualization which provides unlimited set of machines with of almost unlimited capacity. As a AWS EC2 users we generally call these machines as an "instance".


Users can dynamically create,work,expand and shutdown EC2 instances as per use and as per requirement.

Under this blog we will explore how user can create an instances via AWS graphical user interface(GUI). Please follow AWS EC2 CLI to perform same set of process via Command line interface(CLI). So, no more talks let's get started!!!

** Prerequisite:

- AWS Console Access i.e. A valid account on AWS Portal.
- A Valid user with permission of creation and deletion of AWS EC2 Instances.

AWS - Working with EC2 instance via GUI

Please follow below steps to start an EC2 instance via AWS Management Console

1.  Login to AWS Management Console 
Login to AWS Management console and select EC2 from available services. 

 
EC2


2. Select Launch Instance
Click on Launch Instance sub-menu to fire a new EC2 instance.



Launch Instance


3. Choose an AMI (Amazon Machine Image) 

Amazon AMI's are basically pre-configured OS images. There are variety of images available like Windows, Redhat,Ubuntu,Suse etc., select AMI as per requirement and need.Here we are going to select RHEL 7 image.

 
AWS AMI


4. Choose Instance Type


Here we choose type instance Or in simple terms capacity and configuration for our EC2 RHEL instance.

AWS EC2 Instance Types


5. Configure Instance details

Under this step we basically configure our system with set of configurations like Network and Sub-net configurations(VPC),number of instances to be launched, instance access configurations(IAM) & shutdown behavior etc.

Configure Instance Details

6. Add Storage

Step where we configure Or attach additional storage volumes to our instance as per our 
requirement/needs.

Add Storage

Please note EBS i.e. elastic block storage is a term generally used for storage volumes in AWS


7. Assign Tags

Optionally you can assign a tags  like name to your instance to follow any sort of naming convention.

Add Tags


8. Create Security Groups

Security Groups is one of the feature provided by AWS EC2 by which you can setup various sets of firewalls for incoming and outgoing traffic from/to your instances.

 
Security Groups


Setting Up Incoming/Outgoing Firewalls

Here we are allowing SSH default port i.e. port 22 to allow ssh access to our instance.


9. Review and Launch

Review your configurations as performed in steps as above and Launch :-)

 
Review and Launch


Please note while Launching AWS will ask to select available key-pair option i.e. to use an existing key-pair Or create a new key-pair. KP (key-pair) is basically used while login onto an instance and is part of one of the security that is provided by AWS.

10. Keypair
           
           A. Select option - Create a new key-pair and provide a name for it.
           B. Download key-pair.
           C. Once downloaded Click Launch Instances

 
Setup KeyPair


11. Launch Status

Post launching an instance AWS Console Show you launch status page. Now again click on Services -> EC2 and check for running instances

Launch Status


Running Instances


12. Details for Launched/Running Instance

Select running instances reference link to see details for all running instances.

 
Instances
Select any particular instance to see attached details to that instance like IP/VPC/State/Region etc.

 
Instance Details
13. Connecting to an instance

Now we have successfully launched an instance but wondering  how we connect to it ?
To connect to an AWS EC2 instance we have to use key-pair that we generated while launching an instance. We also kept/allowed SSH port to login to RHEL instance via same.

Under EC2 tab there is an option CONNECT which shows straight forward steps to login onto an instance.

 
Connect to an Instance

Default terminal/shell can be used to SSH onto EC2 instance via Linux machines and tools like Putty/Xshell can be used to jump from windows boxes.

SSH  --> ssh -i <key-pair> ec2-user@<IP of EC2 instance> 

 
SSH from Linux Box

Running Commands on EC2 Instance

14. Terminate an Instance

Its always a best practice to terminate an instance when same is not in use which in terms save overall cost for using various services as AWS billing is based upon pay-as-per-usage policy.

 
Terminate an Instance

After termination status of an EC2 instance will changed to "terminated" and same will automatically vanish from the instances list after some default time frame.

Thank You Friends for reading out through this blog , please do post your comments for any sorts of queries or feedback!!!

--Avi



