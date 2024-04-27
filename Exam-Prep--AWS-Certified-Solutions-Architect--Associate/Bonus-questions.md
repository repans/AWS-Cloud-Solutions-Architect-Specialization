```
  *** Do not copy if you are taking the test. ***
```
--- 

# Bonus questions 


#### 01. A company will host a static website within an Amazon S3 bucket. The website will serve millions of users globally, and the company wants to minimize data transfer costs. What should a solutions architect do to ensure costs are kept to a minimum?

- [ ] Implement an AWS Auto Scaling group for the website to ensure it grows with use.
- [ ] Use Cross-Region Replication to copy the website to an additional S3 bucket in a different AWS Region.
- [ ] Move the website to large compute-optimized Amazon EC2 instances with on-demand pricing.
- [x] Create an Amazon CloudFront distribution, with the S3 bucket as the origin server.


#### 02. A solutions architect needs to design a secure environment for AWS resources that are being deployed to Amazon EC2 instances in a VPC. The solution should support a three-tier architecture that consists of web servers, application servers, and a database cluster. The VPC needs to allow resources in the web tier to be accessible from the internet with only the HTTPS protocol. Which combination of actions would meet these requirements? (Select TWO.)

- [ ] Attach Amazon API Gateway to the VPC. Create private subnets for the web, application, and database tiers.
- [x] Attach an internet gateway to the VPC. Create public subnets for the web tier. Create private subnets for the application and database tiers.
- [ ] Attach a virtual private gateway to the VPC. Create public subnets for the web and application tiers. Create private subnets for the database tier.
- [ ] Create a web server security group that allows all traffic from the internet. Create an application server security group that allows requests from only the Amazon API Gateway on the application port. Create a database cluster security group that allows TCP connections from the application security group on the database port only.
- [x] Create a web server security group that allows HTTPS requests from the internet. Create an application server security group that allows requests from the web security group only. Create a database cluster security group that allows TCP connections from the application security group on the database port only.


#### 03. A solutions architect notices an abnormal amount of network traffic coming from an Amazon EC2 instance. The traffic is determined to be malicious, and the destination needs to be determined. What tool can the solutions architect use to identify the destination of the malicious network traffic?

- [ ] Turn on AWS CloudTrail and filter the logs
- [x] Turn on VPC Flow Logs and filter the logs
- [ ] Consult the AWS Health Dashboard
- [ ] Filter the logs from Amazon CloudWatch


#### 04. A SysOps administrator wants to automate the deployment of new SSL/TLS certificates to web servers. The administrator wants a centralized way to keep track and manage the deployed certificates. Which AWS service can the administrator use to meet these requirements?

- [ ] AWS Key Management Service (AWS KMS)
- [ ] Run Command, a capability of AWS Systems Manager
- [x] AWS Certificate Manager (ACM)
- [ ] Parameter Store, a capability of AWS Systems Manager


### 5. A solution architect must create a data store location that will be able to handle different file formats of unknown sizes. The data must be highly available and protected from being accidentally deleted. What solution meets the requirements and is the MOST cost-effective?

- [ ] Deploy an Amazon S3 bucket and activate Cross-Region Replication.
- [ ] Deploy an Amazon DynamoDB table and activate global tables.
- [ ] Deploy a database by using Amazon RDS and configure a Multi-AZ deployment for that database.
- [x] Deploy an Amazon S3 bucket and enable object versioning.


#### 06. A company is migrating its on-premises application to AWS and refactoring the application's design. The design will consist of frontend Amazon EC2 instances that receive requests, backend EC2 instances that process the requests, and a message-queuing service that addresses decoupling the application. A solutions architect has been informed that a key aspect of the application is that requests are processed in the order in which they are received. Which AWS service should the solutions architect use to decouple the application?

- [x] Amazon Simple Queue Service (Amazon SQS) FIFO queue
- [ ] Amazon Simple Queue Service (Amazon SQS) standard queue
- [ ] Amazon Simple Notification Service (Amazon SNS)
- [ ] Amazon Kinesis

#### 07. A gaming company is experiencing exponential growth. On multiple occasions, customers have been unable to access resources. To keep up with the increased demand, management is considering deploying a cloud-based solution. The company wants a solution that can match on-premises resilience of multiple data centers and robust enough to withstand the increased growth activity. Which configuration should a solutions architect implement to meet these requirements?

- [ ] A VPC that is configured with an Elastic Load Balancing (ELB) Network Load Balancer that targets an Amazon EC2 Auto Scaling group consisting of Amazon EC2 instances that span two Availability Zones.
- [ ] A VPC that is configured with an Elastic Load Balancing (ELB) Application Load Balancer that targets an Amazon EC2 Auto Scaling group consisting of Amazon EC2 instances in one Availability Zone.
- [ ] Multiple Amazon EC2 instances that are configured within peered VPCs across two Availability Zones.
- [x] A VPC that is configured with an Elastic Load Balancing (ELB) Application Load Balancer that targets an Amazon EC2 Auto Scaling group consisting of Amazon EC2 instances that span two AWS Regions.


### 8. A company is deploying a production portal application on AWS. The database tier runs on a MySQL database. The company requires a highly available database solution that maximizes ease of management. How can the company meet these requirements?

- [ ] Deploy the database on multiple Amazon EC2 instances that are backed by Amazon Elastic Block Store (Amazon EBS) across multiple Availability Zones. Schedule periodic EBS snapshots.
- [ ] Use Amazon RDS with a Single-AZ deployment. Schedule periodic database snapshots.
- [x] Use Amazon RDS with a Multi-AZ deployment. Schedule periodic database snapshots.
- [ ] Use Amazon DynamoDB with a DynamoDB Accelerator (DAX) cluster. Create periodic on-demand backups.


#### 09. A company requires operating system permission on a relational database server. What should a solutions architect suggest as a configuration for a highly available database architecture?

- [ ] Multiple Amazon EC2 instances in a database replication configuration that uses two Availability Zones
- [ ] A database installed on a single Amazon EC2 instance in an Availability Zone
- [x] Amazon RDS in a Multi-AZ configuration with Provisioned IOPS
- [ ] Multiple Amazon EC2 instances in a replication configuration that uses a placement group


#### 10. A solutions architect must create a disaster recovery (DR) solution for a company's business-critical applications. The DR site must reside in a different AWS Region than the primary site. The solution requires a recovery point objective (RPO) in seconds and a recovery time objective (RTO) in minutes. The solution also requires the deployment of a completely functional but scaled-down version of the applications. Which DR strategy will meet these requirements?

- [ ] Multi-site active-active
- [ ] Backup and restore
- [ ] Pilot light
- [x] Warm standby


#### 11. A financial services company is migrating its multi-tier web application to AWS. The application architecture consists of a fleet of web servers, application servers, and an Oracle database. The company must have full control over the database's underlying operating system. The database must be highly available. Which approach should a solutions architect use for the database tier to meet these requirements?

- [ ] Migrate the database to an Amazon RDS for Oracle DB Single-AZ DB instance.
- [x] Migrate the database to an Amazon RDS for Oracle Multi-AZ DB instance.
- [ ] Migrate to Amazon EC2 instances in two Availability Zones. Install Oracle and configure the instances to operate as a cluster.
- [ ] Migrate to Amazon EC2 instances in a single Availability Zone. Install Oracle and configure the instances to operate as a cluster.

#### 12. A company used Amazon EC2 Spot Instances for a demonstration that is now complete. A solutions architect must remove the Spot Instances to stop them from incurring cost. What should the solutions architect do to meet this requirement?

- [ ] Cancel the Spot request. Terminate the Spot Instances.
- [ ] Cancel the Spot request only.
- [ ] Terminate the Spot Instances only.
- [x] Terminate the Spot Instances. Cancel the Spot request.


#### 13. A company is deploying an environment for a new data processing application. The application will be frequently accessed by 20 different departments across the globe seeking to run analytics. The company plans to charge each department for the cost of that department's access. Which solution will meet these requirements with the LEAST effort?

- [x] Amazon Aurora with global databases. Each department will query a database in a different Region, and the Region is tagged in the billing console.
- [ ] Amazon RDS for PostgreSQL, with read replicas for each department. Each department will query the read replica tagged for their department in the billing console.
- [ ] Amazon Redshift, with clusters set up for each department. Each department will query the cluster tagged for their department in the billing console.
- [ ] Amazon Athena with workgroups set up for each department. Each department will query through the workgroup tagged for their department in the billing console.


#### 14. After reviewing the cost optimization checks in AWS Trusted Advisor, a team finds that it has 10,000 Amazon Elastic Block Store (Amazon EBS) snapshots in its account that are more than 30 days old. The team has determined that it needs to implement better governance for the lifecycle of its resources. Which actions should the team take to automate the lifecycle management of the EBS snapshots with the LEAST effort? (Select TWO.)

- [x] Create and schedule a backup plan with AWS Backup.
- [x] Use Amazon Data Lifecycle Manager.
- [ ] Copy the EBS snapshots to Amazon S3, and then create lifecycle configurations in the S3 bucket.
- [ ] Use a scheduled event in Amazon EventBridge and invoke AWS Step Functions to manage the snapshots.
- [ ] Schedule and run backups in AWS Systems Manager.


#### 15. A company is using an Amazon S3 bucket to store archived data for audits. The company needs long-term storage for the data. The data is rarely accessed and must be available for retrieval the next business day. After a quarterly review, the company wants to reduce the storage cost for the S3 bucket. A solutions architect must recommend the most cost-effective solution to store the archived data. Which solution will meet these requirements?

- [ ] Store the data on an Amazon EC2 instance that uses Amazon Elastic Block Store (Amazon EBS).
- [ ] Store the data in S3 Glacier Flexible Retrieval.
- [x] Use an S3 Lifecycle configuration rule to move the data to S3 Standard-Infrequent Access (S3 Standard-IA).
- [ ] Store the data in another S3 bucket in a different AWS Region.


#### 16. A prediction process requires access to a trained model that is stored in an Amazon S3 bucket. The process takes a few seconds to process an image and make a prediction. The process is not overly resource-intensive, does not require any specialized hardware, and takes less than 512 MB of memory to run. What is the MOST cost-effective compute solution for this use case?

- [ ] Amazon Elastic Container Service (Amazon ECS)
- [ ] Amazon EC2 Spot Instances
- [ ] AWS Elastic Beanstalk
- [x] AWS Lambda functions


#### 17. A hospital is migrating from another cloud provider to AWS and wants to modernize as they migrate. The hospital has containerized applications that run on tablets. During spikes caused by increases in patient visits, the communications from the applications to the central database occasionally fail. As a result, the hospital currently has the applications try to write to the central database once. If that write fails, the application writes to a dedicated application PostgreSQL database run by the hospital IT team on premises. Each of the PostgreSQL databases then sends batch information to the central database. The hospital is asking for recommendations on migrating or refactoring the database write process to lower operational overhead. What should the solutions architect recommend? (Select TWO.)

- [x] Migrate the containerized applications to AWS Fargate.
- [x] Migrate the local databases to Amazon Aurora Serverless PostgreSQL-Compatible Edition.
- [ ] Migrate the PostgreSQL databases to an Amazon RDS instance with a read replica that replaces each of the local databases.
- [ ] Refactor the applications to use Amazon Simple Queue Service (Amazon SQS) and eliminate the local PostgreSQL databases.
- [ ] Refactor the central database to add an Amazon ElastiCache lazy loading cache in front of the database.


#### 18. A company uses Amazon EC2 instances in a test environment. The company has optimized the instances for their current workload. The company uses the instances only during business hours. The company uses Compute Savings Plans and Spot Instances. The company must retain control over the compute resources. A solutions architect must recommend a solution to reduce costs associated with the EC2 instances in the test environment. Which solution will meet these requirements?

- [ ] Use AWS Compute Optimizer and change the instance type or size based on the recommendations.
- [x] Create a time-based Amazon CloudWatch alarm action to start and stop the instances.
- [ ] Use Reserved Instances in addition to the Compute Savings Plan and Spot Instances.
- [ ] Switch from EC2 instances to AWS Lambda functions to optimize the runtime environment.


#### 19. A company is running its application in a single Region on Amazon EC2 with Amazon Elastic Block Store (Amazon EBS) and Amazon S3 as part of the storage design. What should be done to reduce data transfer costs?

- [ ] Create a copy of the compute environment in another AWS Region.
- [ ] Convert the application to run on Lambda@Edge.
- [x] Create an Amazon CloudFront distribution with Amazon S3 as the origin.
- [ ] Replicate Amazon S3 data to buckets in AWS Regions closer to the requester.



--- 
> [Exam Prep: AWS Certified Solutions Architect - Associate](https://www.coursera.org/learn/aws-certified-solutions-architect-associate/)
