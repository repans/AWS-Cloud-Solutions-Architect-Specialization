```
  # Do not copy if you are taking the test.
```
--- 

# Week 1 Assessment


#### 01. A solutions architect must design a solution to help manage their customer’s containerized applications. Currently, the customer workload runs in Docker containers on top of Amazon Elastic Compute Cloud (Amazon EC2) instances and on-premises servers that run a hybrid Kubernetes cluster. The customer wants to migrate part of their hybrid Kubernetes deployment to the cloud with a minimum amount of effort, and they want to keep all the native features of Kubernetes. The customer also wants to reduce their operational overhead for managing their Kubernetes cluster. Which managed AWS service should the solutions architect suggest to best satisfy these requirements?
   - [ ] AWS Fargate with Amazon Elastic Container Service (Amazon ECS)
   - [ ] AWS Fargate with Amazon Elastic Kubernetes Service (Amazon EKS)
   - [ ] Amazon Elastic Container Service (Amazon ECS)
   - [x] Amazon Elastic Kubernetes Service (Amazon EKS)
> Amazon EKS is a managed Kubernetes service that runs Kubernetes in the AWS Cloud and in on-premises data centers. In the cloud, Amazon EKS automatically manages the availability and scalability of the Kubernetes control plane nodes that are responsible for scheduling containers, managing application availability, storing cluster data, and other key tasks.

#### 02. An application needs to process events that are received through an API. Multiple consumers must be able to process the data concurrently. Which AWS managed service would best meet this requirement in the most cost-effective way?
   - [x] Amazon Simple Notification Service (Amazon SNS) with a fan-out strategy
   - [ ] Amazon Simple Queue Service (Amazon SQS) with FIFO queues
   - [ ] Amazon EventBridge with rules
   - [ ] Amazon Elastic Compute Cloud (Amazon EC2) with Spot Instances
> With Amazon SNS, multiple consumers can subscribe to the same topic, permitting to have multiple layers consuming messages at the same time. In addition, Amazon SNS has lower costs than Amazon EventBridge.

### 03. True or False: Amazon Relational Database Service (Amazon RDS) is more suitable for databases that handle structured or relational data, where users can count with features like auto-increment and table joins. Amazon DynamoDB is more suitable for NoSQL database workloads, where tables are collection of items that have their own attributes.
   - [x] True
   - [ ] False
> DynamoDB is a database service for NoSQL data. It is fully managed by AWS. DynamoDB is swift, reliable, and scalable, which makes working with NoSQL data much easier. Amazon RDS is used for relational databases. It is mostly used to handle structured and relational data through Structured Query Language (SQL). 

#### 04. Amazon DynamoDB is designed for scale and performance. In most cases, the DynamoDB response times can be measured in single-digit milliseconds. However, there are certain use cases that require response times in microseconds. For these use cases, DynamoDB Accelerator (DAX) delivers fast response times for accessing eventually consistent data. Which statements about DAX are correct? (Choose THREE.)
   - [x] DAX reduces operational and application complexity by providing a managed service that is compatible with the DynamoDB API.
   - [x] Although using DAX has a cost, it can reduce the consumption of DynamoDB table capacity. If the data is read intensive (that is, millions of requests per second), DAX can result in cost savings by caching the data while also providing better read latency, being beneficial for scenarios in need of repeated reads for individual keys.
   - [ ] DAX does not support server-side encryption (SSE).
   - [x] DAX is not designed for applications that are write-intensive. It can also add cost to applications that do not perform much read activity.
   - [ ] DAX does not support encrypting data in transit, which means that communication between an application and DAX cannot be encrypted.
> - DAX is a managed caching service for Amazon DynamoDB that is compatible with the DynamoDB API.      
> - Through the use of a cache like DAX, you can offload some read requests to the cache, which would save on read capacity for the table itself.    
> - DAX is beneficial for reads because it is a caching service. However, it is not very beneficial for write-heavy workloads.    

#### 05. True or False: AWS Lambda is a compute service that runs code without the need to provision or manage servers. Lambda runs code on a high-availability compute infrastructure. It also performs all the administration of compute resources, including server and operating system maintenance, capacity provisioning and automatic scaling, and logging. Lambda can run code for virtually any type of application or backend service.
   - [x] True
   - [ ] False
> AWS Lambda is a managed compute service that you can use to run serverless compute functions in a highly available and scalable manner.


--- 
> [Architecting Solutions on AWS](https://www.coursera.org/learn/architecting-solutions-on-aws/) {Week-1}

 
