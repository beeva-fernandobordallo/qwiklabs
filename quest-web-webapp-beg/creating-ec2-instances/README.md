# What is it?

Amazon Elastic Compute Cloud = A EC2
Web service with resizable compute capacity in the cloud:

- Complete control of computing resources
- Boot new server instances
- Controlled by web service APIs
- Root access to each instance
- Select and configure: memory, CPU, storage, OS, software packages, ...

Works together with:

- Amazon Simple Storage Service (A S3)
- Amazon SimpleDB
- Amazon Relational Database Service (A RDS)
- Amazon Simple Queue Service (A SQS)
- Amazon Virtual Private Cloud (A VPC)


### Application Machine Images (AMIs)

Amazon provides 'templates' that contain software configuration (OS, App Server, ...). These can be used to launch different TYPES OF INSTANCES.

The instance TYPE used determines the hardware capabilities of the virtual host computer. You can launch multiple instances from an AMI.

The instance FAMILY determines how much throughput and processing cycles are available to your instance.


### Security Groups

- They act as 'firewalls' to control traffic into a group of instances
- You can assign an instance to one or more security groups
- You can add rules to the group to govern inbound traffic

### IP Control for SSH access

In labs there isn't much point but you should control which IPs can access the instance.