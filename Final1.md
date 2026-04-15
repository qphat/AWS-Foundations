## Question 1
**What are advantages of cloud computing for a company moving from a traditional on-premises computing model? (Select TWO.)**

- [ ] IT teams can make capacity decisions before deploying applications so that they always have excess capacity.  
- [x] The company can focus less on infrastructure and focus more on differentiating the business.  
- [x] Resources can be created, scaled up, scaled down, or destroyed based on demand.  
- [ ] The company can invest in more fixed (capital) expenses and reduce their variable expenses.  
- [ ] All on-premises server licenses can be easily transferred and managed centrally in the cloud.  

---

## Question 2
**How does cloud computing improve a company's ability to provision resources to meet capacity demands compared to on-premises computing?**

- [ ] Cloud resources can be locked down to the resource level.  
- [ ] Cloud resources can experience peaks and valleys in usage.  
- [ ] Cloud resources can be cost forecasted.  
- [x] Cloud resources can scale up or down based on demand.  

---

## Question 3
**Which statement accurately describes how customers can use AWS Support?**

- [x] Customers can get AWS Support for both experimental non-production accounts and for business-critical production accounts.  
- [ ] Customers should contact their Support Concierge to provide quick and efficient technical support.  
- [ ] Customers are assigned a Technical Account Manager (TAM) for all AWS Support plans.  
- [ ] Customers must choose one of three support plans: Basic Support, Business Support, and Enterprise Support.  

## Question 4
**A cloud practitioner wants to visualize their AWS costs per EC2 instance type for the past 3 months. Which AWS tool or feature should they use?**

- [ ] AWS Pricing Calculator
- [ ] AWS Budgets
- [x] **AWS Cost Explorer**
- [ ] AWS Bills page


## Question 5
**What is the relationship between AWS Regions, Availability Zones, and data centers?**

- [ ] Each Availability Zone includes data centers. Each data center in an Availability Zone is located in a different geographical Region.  
- [x] Each Region has locations called Availability Zones. Each Availability Zone has data centers. 
- [ ] Each Region has a set of data centers. Each data center maps to one Availability Zone.  
- [ ] A set of data centers in a geographical area create a Region. Availability Zones are connections between Regions.


## Question 6
**An AWS account administrator wants to grant temporary cross-account access that allows external users to access specific resources within their own account. Which action would align with the best practice of using temporary sessions?**

- [ ] Create an AWS Identity and Access Management (IAM) group, grant resource permissions to the group, then add IAM users to the group.  
- [ ] Create an AWS Identity and Access Management (IAM) policy that allows external users to access the specific resources.  
- [ ] Create a new AWS Identity and Access Management (IAM) user account for each user that needs access.  
- [x] **Create an AWS Identity and Access Management (IAM) role that can be assumed by external users and grant it permissions to the specific resources.**


## Question 7
**Which statements about securing data in transit are true? (Select TWO.)**

- [x] **TLS provides encryption of data in transit.** 
- [x] **TLS certificates can be managed using AWS Certificate Manager (ACM).** - [ ] Data moving between AWS services is encrypted using TLS and AWS Key Management Service (AWS KMS).  
- [ ] TLS is a proprietary protocol that's used to secure traffic between AWS virtual private clouds (VPCs).  
- [ ] Web traffic that runs over HTTP is encrypted using TLS.


## Question 8
**A network administrator wants to configure a public subnet and route incoming and outgoing traffic to and from an Amazon EC2 instance in the public subnet to the public internet. Which virtual private cloud (VPC) feature should they use?**

- [ ] A network access control list (ACL)
- [x] **An internet gateway**
- [ ] VPC sharing
- [ ] A network address translation (NAT) gateway


## Question 9
**Which statement accurately describes a content delivery network (CDN)?**

- [ ] A CDN is a Regional group of servers.
- [x] **A CDN caches frequently requested files.**
- [ ] A CDN creates fast connections between origin servers.
- [ ] A CDN speeds up domain name resolution for application servers.



## Question 10
**A company needs to run a short script each time a new item is added to an Amazon S3 bucket. Which compute option meets the need with the least amount of resource provisioning?**

- [x] **Create an AWS Lambda function to run the script whenever a new item is added to the bucket.**
- [ ] Set up the script to run in a container, and deploy the container on Amazon Elastic Container Service (Amazon ECS).
- [ ] Set up a small Amazon EC2 instance that runs code to check for new uploads to the bucket and runs the script.
- [ ] Write a batch job to run the script on all new items overnight when there's less competition for resources. Run the batch job on Spot Instances.


## Question 11
**A developer needs temporary block storage for cache data on an Amazon EC2 instance. Which option should they choose?**

- [ ] Amazon S3
- [x] **Amazon EC2 instance store**
- [ ] Amazon Elastic Block Store (Amazon EBS)
- [ ] Amazon Elastic File System (Amazon EFS)



## Question 12
**Which scenario is a good fit for Amazon Elastic File System (Amazon EFS) storage?**

- [ ] A company needs temporary file storage for its application running on Amazon EC2.
- [x] **A company needs to give all Amazon EC2 instances in its virtual private cloud (VPC) read and write access to a network file system (NFS).**
- [ ] A company wants to build a petabyte-sized data lake for analytics.
- [ ] A company wants to host a website.


## Question 13
**Which statement about AWS storage services is accurate?**

- [x] **To access an Amazon Elastic File System (Amazon EFS), the file system must be mounted on an Amazon EC2 instance in your virtual private cloud (VPC).**
- [ ] Amazon EC2 instance store provides durable storage for the Amazon EC2 instance that it's attached to, but it isn't available to other EC2 instances.  
- [ ] Amazon Elastic Block Store (Amazon EBS) volumes provide temporary block storage to Amazon EC2, but they don't persist when the EC2 instance is stopped.  
- [ ] Amazon EC2 instance store is a good choice for running big data processing and analytics.


## Question 14
**Which statement about Amazon S3 Glacier security is accurate?**

- [ ] The data in Amazon S3 Glacier is public by default.
- [x] **Access to Amazon S3 Glacier can be managed using AWS Identity and Access Management (IAM) policies.**
- [ ] For all operations and interactions with Amazon S3 Glacier, you can use the AWS Management Console.
- [ ] Application encryption must be initiated on objects archived to Amazon S3 Glacier either using the AWS Management Console or programmatically.

## Question 15
**A company has an ecommerce site that requires storage and retrieval of unstructured customer metadata to support one of its microservices. Which database option is best suited to store this data?**

- [ ] Amazon RDS
- [x] **Amazon DynamoDB**
- [ ] Amazon Redshift
- [ ] Amazon Aurora


## Question 16
**What is an attribute in an Amazon DynamoDB table?**

- [ ] A key that uniquely identifies a set of data elements
- [x] **A data element that doesn't need to be broken down further**
- [ ] A set of related data
- [ ] A data element that is shared by all items in a table


## Question 17
**How does AWS Trusted Advisor assist a company getting started with AWS?**

- [ ] AWS Trusted Advisor provides recommendations for migrating on-premises resources to the cloud.  
- [ ] AWS Trusted Advisor automatically increases service limits (quotas) if you're near the limit.  
- [ ] AWS Trusted Advisor prevents access to resources that have overly broad permissions.  
- [x] **AWS Trusted Advisor provides recommendations on configuring your AWS resources.**



## Question 18
**For which type of use case is it usually OK to have 2 nines of availability (99%)?**

- [ ] Online commerce
- [ ] ATM transactions
- [ ] Internet of Things (IoT) applications
- [x] **Batch processing**


## Question 19
**A company has an application running on two Amazon EC2 instances. They want to reduce idle EC2 capacity. The application load is difficult to forecast, and they want to keep the CPU utilization close to 40 percent on all instances. Which type of Amazon EC2 Auto Scaling should they configure?**

- [ ] Predictive scaling
- [x] **Dynamic scaling**
- [ ] Manual scaling
- [ ] Scheduled scaling



## Question 20
**Which statement accurately describes how Amazon EC2 Auto Scaling is used?**

- [x] **Amazon EC2 Auto Scaling is useful for predictable workloads.**
- [ ] Amazon EC2 Auto Scaling allows an application to automatically add resources, but it can't automatically scale them back down.  
- [ ] The size of an Amazon EC2 Auto Scaling group will scale up and down automatically based on its configuration and the number of instances can't be manually adjusted.  
- [ ] Amazon EC2 Auto Scaling is useful for dynamic, unpredictable workloads but doesn't add much value for predictable workloads.


