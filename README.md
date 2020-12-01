# AWS Cloud Services - Getting Started with AWS
To host the project/website on amazon aws web service for within minutes, use the following quick and easy steps:

Step 1: Login to the aws console
Step 2: Choose Launch Instance 
Step 3: Choose AIM (Amazon Machine Image)
Step 4: Choose EC2 Instance Types
Step 5: Configure Instance Details
Step 6: Add Storage of Ec2 Intance
Step 7: Tag Instance of Ec2 Instance
Step 8: Configure Security Groups
Step 9: Review Instances
Step 10: Create Key-Pair For Intance Access
Step 11: Type Ec2 Instance Public Ip On Browser
Step 12: Connect Instance 

# Step 1: Login to the aws console
Use this link https://console.aws.amazon.com/ec2/ to login in your aws console account. If you have not registered with amazon aws. You can also click this link and create your amazon aws account for free.

# Step 2: Choose Launch Instance 
First of all, Click on ‘Launch Instance’ button shows in the below picture for launch/create new ec2 intance in aws:

# Step 3: Choose an Amazon Machine Image (AMI)Cancel and Exit
An AMI is a template that contains the software configuration (operating system, application server, and applications) required to launch your instance. You can select an AMI provided by AWS, our user community, or the AWS Marketplace; or you can select one of your own AMIs.

# Step 4: Choose an Instance Type
Amazon EC2 provides a wide selection of instance types optimized to fit different use cases. Instances are virtual servers that can run applications. They have varying combinations of CPU, memory, storage, and networking capacity, and give you the flexibility to choose the appropriate mix of resources for your applications. Learn more about instance types and how they can meet your computing needs.

# Step 5: Configure Instance Details
Configure the instance to suit your requirements. You can launch multiple instances from the same AMI, request Spot instances to take advantage of the lower pricing, assign an access management role to the instance, and more.

# Step 6: Add Storage
Your instance will be launched with the following storage device settings. You can attach additional EBS volumes and instance store volumes to your instance, or edit the settings of the root volume. You can also attach additional EBS volumes after launching an instance, but not instance store volumes. Learn more about storage options in Amazon EC2.

# Step 7: Add Tags
A tag consists of a case-sensitive key-value pair. For example, you could define a tag with key = Name and value = Webserver.
A copy of a tag can be applied to volumes, instances or both. Tags will be applied to all instances and volumes. Learn more about tagging your Amazon EC2 resources.

# Step 8: Configure Security Group
A security group is a set of firewall rules that control the traffic for your instance. On this page, you can add rules to allow specific traffic to reach your instance. For example, if you want to set up a web server and allow Internet traffic to reach your instance, add rules that allow unrestricted access to the HTTP and HTTPS ports. You can create a new security group or select from an existing one below. Learn more about Amazon EC2 security groups.

# Step 9: Review Instance Launch
Please review your instance launch details. You can go back to edit changes for each section. Click Launch to assign a key pair to your instance and complete the launch process.
