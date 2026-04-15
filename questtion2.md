## Question 1
**Which IT requirement would lead an architect to choose an infrastructure as a service (IaaS) cloud service model?**

- [ ] A company wants to use a web-based email solution.  
- [ ] A company wants to run a managed instance for the marketplace.  
- [x] **A company wants to maintain the highest level of flexibility over its IT resources.** 
- [ ] A company wants to maintain control of its applications but avoid maintaining servers and operating systems.

## Question 2
**Which statement describes the business perspective of the AWS Cloud Adoption Framework?**

- [x] **Stakeholders can create a strong business case for cloud adoption and prioritize cloud adoption initiatives.**
- [ ] Stakeholders can use architectural dimensions and models to understand and communicate the nature of IT systems and their relationships.  
- [ ] Stakeholders can evaluate organizational structures and roles, new skill and process requirements, and identify gaps.  
- [ ] Stakeholders can focus on the skills and processes that are needed to align IT strategy and goals with business strategy and goals.

## Question 3
**Which statements about how a company would use AWS Organizations are accurate? (Select TWO.)**

- [x] **A company can consolidate and centrally manage multiple AWS accounts.**
- [ ] A company can only manage AWS Organizations through the AWS Management Console.
- [x] **A company can benefit from volume discounts with consolidated billing.**
- [ ] A company can use AWS Organizations' consolidated identity and access management (IAM) feature to replace the existing IAM system for an individual account.
- [ ] A company can use AWS Organizations to create security groups that control access to resources.

## Question 4
**How does the AWS Billing Dashboard help companies analyze their AWS usage to find potential cost-saving opportunities?**

- [ ] The billing dashboard lists all AWS accounts with activity in the previous 6 months and a summary of spending for each account.
- [ ] The billing dashboard shows the pricing models for all the AWS services that are used in your account and where your usage falls in the AWS Free Tier.
- [x] **The billing dashboard shows the status of the month-to-date AWS expenditure and the AWS services that account for the majority of the overall expenditure.**
- [ ] The billing dashboard lists the costs that were incurred over the past month by service, by AWS Region, and by linked accounts.


## Question 5
**Which statement about AWS Regions is true?**

- [ ] All available Regions are enabled by default in an AWS account.
- [ ] All AWS accounts can access all AWS Regions.
- [ ] Data stored in an AWS Region isn't subject to geographical compliance requirements.
- [x] **Using a Region as close as possible to users can reduce latency.**


## Question 6
**Which statements about AWS Identity and Access Management (IAM) policies are accurate? (Select TWO.)**

- [x] **Access control lists (ACLs) are a form of resource-based policies.**
- [ ] Identity-based policies can only be attached to a single entity.  
- [ ] Resource-based policies are attached to a user, group, or role.  
- [ ] Resource-based policies allow access by default.  
- [x] **Identity-based policies are attached to a user, group, or role.**



## Question 7
**Which scenario describes a use case for AWS CloudTrail?**

- [x] **An account administrator wants the ability to track user activity on their account.**
- [ ] A systems administrator wants to protect their web application from denial of service attacks.
- [ ] An account administrator wants to centrally control access permissions for groups of accounts.
- [ ] A developer wants to control user logins to their website.


## Question 8
**A network administrator wants to run their ecommerce web application on a virtual private cloud (VPC). Which step is part of setting up the VPC? (Select TWO.)**

- [x] **Create private and public subnets.**
- [ ] Delete the local route in the route table.
- [x] **Specify the range of IP addresses for the VPC.**
- [ ] Create the main route table.
- [ ] Attach the VPC to a security group.

## Question 9
**Which statement accurately describes a content delivery network (CDN)?**

- [x] **A CDN caches frequently requested files.**
- [ ] A CDN is a Regional group of servers.
- [ ] A CDN speeds up domain name resolution for application servers.
- [ ] A CDN creates fast connections between origin servers.


## Question 10
**A company wants complete control over its server's configurations, operating system (OS), and application software stack. Which AWS compute service should they choose?**

- [ ] AWS Lambda
- [x] **Amazon EC2**
- [ ] Amazon RDS
- [ ] Amazon Elastic Container Service (Amazon ECS)



## Question 11
**A developer needs temporary block storage for cache data on an Amazon EC2 instance. Which option should they choose?**

- [ ] Amazon S3
- [x] **Amazon EC2 instance store**
- [ ] Amazon Elastic File System (Amazon EFS)
- [ ] Amazon Elastic Block Store (Amazon EBS)


## Question 12
**Which scenario is a good fit for Amazon Elastic File System (Amazon EFS) storage?**

- [ ] A company needs temporary file storage for its application running on Amazon EC2.
- [x] **A company needs to give all Amazon EC2 instances in its virtual private cloud (VPC) read and write access to a network file system (NFS).**
- [ ] A company wants to build a petabyte-sized data lake for analytics.
- [ ] A company wants to host a website.


## Question 13
**A company uploads PDF forms to Amazon S3 that must be retained for 1 year. The forms are rarely accessed after 1 week, but they must be available within 1 day when they're requested. What lifecycle policy is the most cost-effective for their needs?**

- [ ] Move objects from Amazon Standard-Infrequent Access to Amazon S3 Standard after 1 week.
- [ ] **Move objects from Amazon S3 Standard to Amazon S3 Standard-Infrequent Access after 7 days.**
- [ ] Move objects from Amazon S3 Standard to Amazon S3 One Zone-Infrequent Access after 7 days. Delete the objects after 365 days.
- [x] Move objects from Amazon S3 Standard to Amazon S3 Glacier after 7 days. Delete them after 365 days.


## Question 14
**Which scenario describes a good use case for Amazon S3 Standard storage?**

- [ ] Act as an EC2 instance store.
- [x] **Hosting website images**
- [ ] Running a relational database
- [ ] Sharing an NFS file system


## Question 15
**A company has an ecommerce site that requires storage and retrieval of unstructured customer metadata to support one of its microservices. Which database option is best suited to store this data?**

- [x] **Amazon DynamoDB**
- [ ] Amazon RDS
- [ ] Amazon Redshift
- [ ] Amazon Aurora


## Question 16
**Which scenario is a good fit for Amazon Redshift?**

- [ ] A company needs a relational database for a line-of-business transactional database.
- [x] **A company needs a data warehouse to support analytics applications.**
- [ ] A company needs a database for managing unstructured data.
- [ ] A company needs to store large volumes of mixed media image and video files.


## Question 17
**Which statement reflects a design principle of the Reliability pillar of the AWS Well-Architected Framework?**

- [ ] Don’t deploy code to production until you’re certain that it can’t fail.
- [ ] Scale vertically to the largest instance types that your budget allows based on your best guess of capacity.
- [x] **Replace one large resource with multiple, smaller resources, and distribute requests across these smaller resources.**
- [ ] Limit automation when updating infrastructure.


## Question 18
**What type of alert might be provided by AWS Trusted Advisor?**

- [x] An alert that multi-factor authentication (MFA) isn’t activated on an AWS account
- [ ] An alert of unusual API calls made in an AWS account
- [ ] An alert of unauthorized access in an AWS account
- [ ] **An alert that an AWS Identity and Access Management (IAM) user has requested service quota changes**


## Question 19
**A company has an application running on two Amazon EC2 instances. They want to reduce idle EC2 capacity. The application load is difficult to forecast, and they want to keep the CPU utilization close to 40 percent on all instances. Which type of Amazon EC2 Auto Scaling should they configure?**

- [ ] Scheduled scaling
- [x] **Dynamic scaling**
- [ ] Predictive scaling
- [ ] Manual scaling



## Question 20
**How is Elastic Load Balancing (ELB) used with Amazon EC2 Auto Scaling? (Select TWO).**

- [x] **ELB performs health checks on new Amazon EC2 instances that are added to the Amazon EC2 Auto Scaling group.**
- [x] **ELB distributes traffic between Amazon EC2 instances in an Amazon EC2 Auto Scaling group.**
- [ ] ELB triggers an Amazon EC2 Auto Scaling event when a threshold is reached.
- [ ] ELB establishes the minimum and maximum number of instances in the Amazon EC2 Auto Scaling group.
- [ ] ELB automatically adds new instances to the Amazon EC2 Auto Scaling group when the load reaches a predetermined limit.