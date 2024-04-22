```
  # Do not copy if you are taking the test.
```
--- 

# Week 3 Quiz


### 01. What is a typical use case for Amazon Simple Storage Service (Amazon S3)?
   - [x] Object storage for media hosting
   - [ ] Object storage for a boot drive
   - [ ] Block storage for an Amazon Elastic Compute Cloud (Amazon EC2) instance
   - [ ] File storage for multiple Amazon Elastic Compute Cloud (Amazon EC2) instances
   > Amazon S3 is an object storage service that is designed for large objects, such as media files. Because users can store unlimited objects, and the size of each individual object can be up to 5 TB, Amazon S3 is a good location to host video, photo, or music uploads. For more information, see the Object Storage with Amazon S3 video. 


### 02. A company needs a storage layer for a high-transaction relational database on an Amazon Elastic Compute Cloud (Amazon EC2) instance. Which service should the company use?
   - [ ] Amazon EC2 Instance Store
   - [x] Amazon Elastic Block Store (Amazon EBS)
   - [ ] Amazon Simple Storage Service (Amazon S3)
   - [ ] Amazon Elastic File System (Amazon EFS)
> Amazon EBS works well for a high-transaction database storage layer. For more information, see the Amazon EC2 Instance Storage and Amazon Elastic Block Store video.

### 03. True or False: Amazon Elastic Block Store (Amazon EBS) volumes are considered ephemeral storage.
   - [ ] True
   - [x] False
> Amazon EBS provides persistent storage. If the Amazon Elastic Compute Cloud (Amazon EC2) instance is stopped or terminated, data that is attached to the EC2 instance will remain on an associated EBS volume permanently. For more information, see the Amazon EC2 Instance Storage and Amazon Elastic Block Store reading.

### 04. A solutions architect is working for a healthcare facility, and they are tasked with storing 7 years of patient information that is rarely accessed. The facility’s IT manager asks the solutions architect to consider one of the Amazon Simple Storage Service (Amazon S3) storage tiers to store the patient information. Which storage tier should the solutions architect suggest?
   - [ ] Amazon S3 Standard
   - [x] Amazon S3 Glacier Deep Archive
   - [ ] Amazon S3 Standard-Infrequent Access
   - [ ] Amazon S3 Intelligent-Tiering
> Amazon S3 Glacier Deep Archive is the lowest-cost storage class in Amazon S3. This storage class supports long-term retention and digital preservation for data that might be accessed once or twice in a year. It is designed for customers—particularly those in highly regulated industries, such as financial services, healthcare, and the public sector—that retain data sets for 7 to 10 years (or longer) to meet regulatory compliance requirements. For more information, see the Object storage with Amazon S3 reading. 

### 05. True or False: Object storage is the best storage solution for applications that need to frequently update specific small sections of a file.
   - [ ] True
   - [x] False
> User can update only the entire file in object storage. To update specific sections of a file, we recommend using block storage. For more information, see Storage Types on AWS.

### 06. True or False: A Multi-AZ deployment is beneficial when users want to increase the availability of their database.
   - [x] True
   - [ ] False
> Placing a workload across multiple Availability Zones increases the availability of resources. For example, say that an environmental hazard in an Availability Zone causes an Amazon Aurora database to stop working. In this case, a read-replica of the Aurora database instance that is in an unaffected Availability Zone will automatically be promoted to a primary database instance. For more information, see Amazon Relational Database Service.

### 07. Which task of running and operating the database are users responsible for when they use Amazon Relational Database Service (Amazon RDS)?
   - [x] Optimizing the database
   - [ ] Provisioning and managing the underlying infrastructure
   - [ ] Installing the relational database management system on the database instance
   - [ ] Installing patches to the operating system for the database instance
> With Amazon RDS, users are no longer responsible for the underlying environment that the database runs on. Instead, users can focus on optimizing the database because Amazon RDS has components that AWS manages. For more information, see Explore Databases on AWS.

### 08. Which of the following are common use cases for file storage? (Choose TWO.)
   - [x] User home directories
   - [ ] Backup files that are stored in Amazon Simple Storage Service (Amazon S3)
   - [x] Large content repositories
   - [ ] Relational or non-relational databases
   - [ ] Big data analytics
> User home directories are an example of file storage that uses a hierarchical system to store and organize data. For more information, see Reading: Storage types on AWS.
> Large content repositories are an example of file storage. They use a hierarchical system to store and organize data. For more information, see Reading: Storage types on AWS. 

### 09. True or False: The IT department in a company can attach Amazon Elastic Block Store (Amazon EBS) volumes to Amazon Simple Storage Service (Amazon S3) to store data in a bucket.
   - [ ] True
   - [x] False
> The IT department cannot attach EBS volumes to Amazon S3. Instead, Amazon EBS can only be attached to Amazon Elastic Compute Cloud (Amazon EC2) instances. For more information, see Choose the right storage service.

### 10. Which of the following instance families does Amazon Relational Database Service (Amazon RDS) support? (Choose TWO.)
   - [ ] Storage optimized
   - [x] General purpose
   - [ ] Compute optimized
   - [x] Memory optimized
   - [ ] Accelerated computing
> Amazon RDS supports general-purpose instances. For more information, see Reading: Amazon Relational Database Service. 
> Amazon RDS is optimized for memory-intensive applications. For more information, see Reading: Amazon Relational Database Service. 

### 11. A solutions architect is working for a small business. The business is looking for a storage service that temporarily stores frequently changing and non-persistent data. This type of data can be deleted during instance stops or terminations. Which service should the solutions architect recommend for this use case?
   - [ ] Amazon Elastic Block Store (Amazon EBS)
   - [ ] Amazon Simple Storage Service (Amazon S3)
   - [x] Amazon Elastic Compute Cloud (Amazon EC2) Instance Store
   - [ ] Amazon Elastic File System (Amazon EFS)
> Amazon EC2 Instance Store provides ephemeral block storage that is well suited for the temporary storage of information, such as buffers, caches, and scratch data. For more information, see Reading: Choose the right storage service. 

### 12. Which database is a non-relational database that stores data in key-value pairs, and is a good fit for hosting simple lookup tables?
   - [x] Amazon DynamoDB
   - [ ] Amazon DocumentDB
   - [ ] Amazon Neptune
   - [ ] Amazon Relational Database Service (Amazon RDS)
> DynamoDB is a database that uses the key-value data model for storing simple data. For more information about the correct question, see Purpose Built Databases on AWS. 

### 13. Which core component of Amazon DynamoDB corresponds to a column in a relational database table?
   - [ ] Table
   - [ ] Item
   - [x] Attribute
   - [ ] Database
> In DynamoDB, an attribute is a fundamental data element. It is something that does not need to be broken down any further. For more information, see Reading: Introduction to Amazon DynamoDB. 

### 14. Which AWS database service is best suited for use cases such as social networking or recommendation engines?
   - [ ] Amazon DynamoDB
   - [ ] Amazon Aurora
   - [ ] Amazon Redshift
   - [x] Amazon Neptune
> Amazon Neptune is a fast, reliable, fully managed graph database service that is designed for fraud detection, social networking, recommendation engines, and more. For more information, see Reading: Choose the right AWS database service. 



--- 
> [AWS Cloud Technical Essentials](https://www.coursera.org/learn/aws-cloud-technical-essentials/) {Week-3}
