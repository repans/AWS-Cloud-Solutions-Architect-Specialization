```
  # Do not copy if you are taking the test.
```
--- 

# Week 3 Assessment


#### 01. Which of the following options includes true statements for both Amazon Simple Storage Service (Amazon S3) cross-Region replication and AWS Key Management Service (AWS KMS)?
   - [ ] To configure Amazon S3 cross-Region replication, both the source and destination buckets must belong to the same AWS account. Server-side encryption (SSE) is possible for replicated objects.
   - [ ] To configure Amazon S3 cross-Region replication, both the source and destination buckets must belong to the same AWS account. Server-side encryption (SSE) is not possible for replicated objects.
   - [x] To configure Amazon S3 cross-Region replication, the source and destination buckets can belong to different AWS accounts. Server-side encryption (SSE) is possible for replicated objects.
   - [ ] To configure Amazon S3 cross-Region replication, the source and destination buckets can belong to different AWS accounts. Server-side encryption is not possible for replicated objects.
> Both statements are true. Buckets can belong to different accounts. SSE (powered by Amazon KMS) can be enabled for the replicated objects. For more information, see 
[Replicating objects](https://docs.aws.amazon.com/AmazonS3/latest/userguide/replication.html).

#### 02. A solutions architect is designing a hybrid solution. The solution uses Amazon Virtual Private Cloud (Amazon VPC) resources, such Amazon Relational Database Service (Amazon RDS) and Amazon Elastic Compute Cloud (Amazon EC2). It also uses services that are not in a VPC, such as Amazon Simple Storage Service (Amazon S3) and AWS Systems Manager. Which statements about Amazon VPC and the scope of AWS services are correct? (Choose THREE.)
   - [x] Amazon VPC gives the user full control over their virtual networking environment. Therefore, the solutions architect can define firewall rules on the networking level for VPC-based resources.
   - [ ] Because S3 buckets do not reside inside a VPC, the customer can rely on AWS to configure security mechanisms, such as permissions and bucket policies. Thus, security is automatically applied on the data level because this level of security is the responsibility of AWS.
   - [x] VPC-based services that reside in a private subnet require specific configurations to enable internet access, such as a NAT gateway and route tables.
   - [ ] When possible, customers should avoid having services reside in VPCs because a networking misconfiguration can accidentally leave the infrastructure in an unsafe state.
   - [ ] Using AWS resources like Amazon S3 is less secure because they are public resources by default.
   - [x] AWS VPN solutions can be configured to establish secure connections between on-premises networks, remote offices, client devices, and the AWS global network.
> - You can use Amazon VPC to launch AWS resources in a virtual network that you have defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.
> - Route tables are configured to route packets to specific destinations, and you can configure them in a VPC. If you want to allow internet access from private subnets, you can create a NAT gateway (or a NAT instance that is configured to forward packets) and change private route tables to point to that resource for internet destinations. This configuration would allow the private subnet to have outgoing access to the internet, without exposing it to incoming requests from the internet.
> - You can use AWS VPN to administratively access VPC resources from on-premises networks. AWS VPN comprises two services—AWS Site-to-Site VPN and AWS Client VPN—which means that single computers can connect with the help of a client, or two entire network scopes can also be connected. With the correct routing, you can even access VPC resources that sit in private subnets.  

#### 03. Which statements about AWS Storage Gateway are correct? (Choose THREE.)
   - [x] AWS Storage Gateway is a set of hybrid cloud storage services that provide on-premises access to virtually unlimited cloud storage.
   - [ ] AWS Storage Gateway offers virtually unlimited cloud storage to users and applications, at the cost of new storage hardware.
   - [x] AWS Storage Gateway delivers data access to on-premises applications while taking advantage of the agility, economics, and security capabilities of the AWS Cloud.
   - [ ] AWS Storage Gateway is limited to only on-premises applications, which means that it cannot be used from cloud to cloud.
   - [x] AWS Storage Gateway helps support compliance requirements through integration with AWS Backup to manage the backup and recovery of Volume Gateway volumes, which simplifies backup management.
   - [ ] AWS Storage Gateway can only work as an Amazon S3 File Gateway.
> - You can use Storage Gateway in on-premises environments so that on-premises networks can access cloud storage resources. Storage Gateway works well in hybrid scenarios, such as the one that Morgan designed for this week’s architecture.
> - You can use Storage Gateway during only the times that you need it, which means that you can take advantage of the economics and security capabilities of the cloud.
> - Integration with AWS Backup is supported by Storage Gateway, more information [here](https://aws.amazon.com/storagegateway/features/) 


#### 04. Which set of AWS services is the BEST fit for the “Object, file, and block storage” category (which means that the services are dedicated to storing data in a durable way)?
   - [ ] AWS DataSync, AWS Snow Family
   - [x] Amazon Simple Storage Service (Amazon S3), Amazon Elastic File System (Amazon EFS), Amazon Elastic Block Store (Amazon EBS), Amazon FSx
   - [ ] AWS Storage Gateway, AWS Snow Family
   - [ ] AWS Elastic Disaster Recovery, AWS Backup
> According to the Cloud Storage on AWS page, Amazon S3, Amazon EFS, Amazon EBS, and Amazon FSx belong to the “Object, file, and block storage” category. Amazon S3 is designed to store virtually any amount of data from virtually anywhere. Amazon EFS automatically grows and shrinks as you add and remove files, and it reduces the need for management or provisioning. Amazon EBS is an easy-to-use, scalable, high-performance block-storage service that is designed for Amazon Elastic Compute Cloud (Amazon EC2). Amazon FSx makes it easier to provide broadly-accessible and highly-performant file storage for a wide variety of use cases. For more information, see 
[Cloud Storage](https://aws.amazon.com/products/storage) on AWS.


#### 05. True or False: Amazon Simple Storage Service (Amazon S3) is better than Amazon Elastic Block Store (Amazon EBS) because it is designed to provide a higher level of data durability.
   - [ ] True
   - [x] False
> This question statement is not true. Throughout this course, Raf and Morgan have been reinforcing the message that there is no one better service, but the most appropriate one for customer needs. If a customer needs to have access to block-level storage, Amazon EBS is better suited for the job. If the customer need a place to store static assets, Amazon S3 could be better. There is no way to affirm one service is better than another without looking at the requirements.   


--- 
> [Architecting Solutions on AWS](https://www.coursera.org/learn/architecting-solutions-on-aws/) {Week-3}

 
