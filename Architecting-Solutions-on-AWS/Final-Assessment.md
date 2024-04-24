```
  # Do not copy if you are taking the test.
```
--- 

# Final Assessment


#### 01. A solutions architect must design a solution to help manage their customer’s containerized applications. Currently, the customer workload runs in Docker containers on top of Amazon Elastic Compute Cloud (Amazon EC2) instances and on-premises servers that run a hybrid Kubernetes cluster. The customer wants to migrate part of their hybrid Kubernetes deployment to the cloud with a minimum amount of effort, and they want to keep all the native features of Kubernetes. The customer also wants to reduce their operational overhead for managing their Kubernetes cluster. Which managed AWS service should the solutions architect suggest to best satisfy these requirements?
   - [ ] AWS Fargate with Amazon Elastic Container Service (Amazon ECS)
   - [ ] AWS Fargate with Amazon Elastic Kubernetes Service (Amazon EKS)
   - [ ] Amazon Elastic Container Service (Amazon ECS)
   - [x] Amazon Elastic Kubernetes Service (Amazon EKS)

#### 02. An application needs to process events that are received through an API. Multiple consumers must be able to process the data concurrently. Which AWS managed service would best meet this requirement in the most cost-effective way?
   - [x] Amazon Simple Notification Service (Amazon SNS) with a fan-out strategy
   - [ ] Amazon Simple Queue Service (Amazon SQS) with FIFO queues
   - [ ] Amazon EventBridge with rules
   - [ ] Amazon Elastic Compute Cloud (Amazon EC2) with Spot Instances

#### 03. True or False: Amazon Relational Database Service (Amazon RDS) is more suitable for databases that handle structured or relational data, where users can count with features like auto-increment and table joins. Amazon DynamoDB is more suitable for NoSQL database workloads, where tables are collection of items that have their own attributes.
   - [x] True
   - [ ] False

#### 04. Amazon DynamoDB is designed for scale and performance. In most cases, the DynamoDB response times can be measured in single-digit milliseconds. However, there are certain use cases that require response times in microseconds. For these use cases, DynamoDB Accelerator (DAX) delivers fast response times for accessing eventually consistent data. Which statements about DAX are correct? (Choose THREE.)
   - [x] DAX reduces operational and application complexity by providing a managed service that is compatible with the DynamoDB API.
   - [x] Although using DAX has a cost, it can reduce the consumption of DynamoDB table capacity. If the data is read intensive (that is, millions of requests per second), DAX can result in cost savings by caching the data while also providing better read latency, being beneficial for scenarios in need of repeated reads for individual keys.
   - [ ] DAX does not support server-side encryption (SSE).
   - [x] DAX is not designed for applications that are write-intensive. It can also add cost to applications that do not perform much read activity.
   - [ ] DAX does not support encrypting data in transit, which means that communication between an application and DAX cannot be encrypted.

#### 05. True or False: AWS Lambda is a compute service that runs code without the need to provision or manage servers. Lambda runs code on a high-availability compute infrastructure. It also performs all the administration of compute resources, including server and operating system maintenance, capacity provisioning and automatic scaling, and logging. Lambda can run code for virtually any type of application or backend service.
   - [x] True
   - [ ] False

#### 06. A solutions architect is designing a solution that needs real-time data ingestion. They are considering either Amazon Kinesis Data Firehose or Amazon Kinesis Data Streams for this solution. Which service should the solutions architect choose to meet the requirement for real-time data ingestion, and why? (Remember that lower data latency means a lower roundtrip time from when data is ingested and available.)
   - [ ] Amazon Kinesis Data Firehose, because it has lower latency when compared to Amazon Kinesis Data Streams
   - [ ] Amazon Kinesis Data Firehose, because it has higher latency when compared to Amazon Kinesis Data Streams
   - [x] Amazon Kinesis Data Streams, because it has lower latency when compared to Amazon Kinesis Data Firehose
   - [ ] Amazon Kinesis Data Streams, because it has higher latency when compared to Amazon Kinesis Data Firehose

#### 07. A solutions architect is designing a serverless solution that can do Structured Query Language (SQL) queries over multiple objects that are stored in Amazon Simple Storage Service (Amazon S3). All the objects share the same data structure (schema) and are in JSON. Which service would make it easier to query the data, in addition to providing serverless capabilities?
   - [x] Amazon Athena
   - [ ] AWS Database Migration Service (AWS DMS)
   - [ ] Amazon S3 Select
   - [ ] AWS Data Exchange

#### 08. True or False: When architecting a solution that can handle high demand and usage spikes, Amazon CloudFront should be used in front of an Amazon Simple Storage Service (Amazon S3) bucket. CloudFront can cache data that gets delivered to customers, and it lets customers use custom domain names. In addition, CloudFront can serve custom SSL certificates that are issued by Amazon Certificate Manager (at no additional cost) and it can provide distributed denial of service (DDoS) protection that is powered by AWS WAF and AWS Shield.
   - [x] True
   - [ ] False

#### 09. A solutions architect is designing a hybrid solution. The solution uses Amazon Virtual Private Cloud (Amazon VPC) resources, such Amazon Relational Database Service (Amazon RDS) and Amazon Elastic Compute Cloud (Amazon EC2). It also uses services that are not in a VPC, such as Amazon Simple Storage Service (Amazon S3) and AWS Systems Manager. Which statements about Amazon VPC and the scope of AWS services are correct? (Choose THREE.)
   - [x] Amazon VPC gives the user full control over their virtual networking environment. Therefore, the solutions architect can define firewall rules on the networking level for VPC-based resources.
   - [ ] Because S3 buckets do not reside inside a VPC, the customer can rely on AWS to configure security mechanisms, such as permissions and bucket policies. Thus, security is automatically applied on the data level because this level of security is the responsibility of AWS.
   - [x] VPC-based services that reside in a private subnet require specific configurations to enable internet access, such as a NAT gateway and route tables.
   - [ ] When possible, customers should avoid having services reside in VPCs because a networking misconfiguration can accidentally leave the infrastructure in an unsafe state.
   - [ ] Using AWS resources like Amazon S3 is less secure because they are public resources by default.
   - [x] AWS VPN solutions can be configured to establish secure connections between on-premises networks, remote offices, client devices, and the AWS global network.

#### 10. What are some benefits of using multiple AWS accounts with AWS Organizations? (Choose THREE.)
   - [x] Grouping workloads based on business purpose and ownership
   - [ ] Using different payment methods per account
   - [x] Limiting the scope of impact from adverse events
   - [x] Distributing AWS service quotas and API request rate limits
   - [ ] Having multiple account root users with unrestricted access on each account
> - One of the patterns for organizing AWS account usage is to group workloads based on business purpose or ownership.
> - Using multiple AWS accounts through AWS Organizations can limit the scope of impact for adverse events by helping resources achieve independence and isolation, and reducing the blast radius of potential incidents.
> - A benefit of using multiple AWS accounts is the ability to distribute AWS service quotas and API request rate limits across accounts, instead of everything applying to only one account.  


### 11. True or False: A service control policy (SCP) statement with an explicit deny prevents even the account root user from performing API calls.
   - [x] True
   - [ ] False
> SCPs govern policies on the account level. After permissions have been explicitly denied in an SCP, the action cannot be allowed. Even the root user will not be able to perform the denied action.  


#### 12. A solutions architect is designing a solution that provides single sign-on (SSO) to authenticate into AWS accounts that are in AWS Organizations. Which AWS service can the solutions architect use to implement identity federation with existing identity providers, such as Microsoft Active Directory?
   - [ ] AWS Identity and Access Management (IAM) users
   - [ ] Amazon CloudWatch
   - [x] AWS IAM Identity Center (successor to AWS Single Sign-On)
   - [ ] AWS CloudTrail
> IAM Identity Center is the best candidate for this task because it offers integration with third-party identity providers (IdPs). Supported identity sources include Microsoft Active Directory Domain Services and external identity providers, such as Okta Universal Directory or Microsoft Azure Active Directory (Azure AD).  

#### 13. Which statements are best practices for multi-account environments? (Choose THREE.)
   - [x] Enable Amazon CloudWatch billing alarms per account and configure tagging policies in AWS Organizations.
   - [ ] Give AdministratorAccess policies to developers in their development AWS accounts.
   - [x] Prevent CloudTrail configuration from being disabled in the shared services account.
   - [x] Use multi-factor authentication (MFA) for users in centralized credentialing, such as using AWS IAM Identity Center (successor to AWS Single Sign-On).
   - [ ] Reuse passwords for simplicity and ease of access.
   - [ ] Provide powerful users and broad roles for Cloud Center of Excellence (CCoE) members, such as granting AdministratorAccess permissions to them.
> - These actions are good practices because they give the architect visibility into the cost per account. Additionally, a feature called Cost Anomaly Detection can be enabled in the AWS Cost Management portal. You can provide monitoring for linked accounts in AWS Organizations, having automated cost anomaly detection and root cause analysis if something goes wrong.
> - Preventing CloudTrail from being disabled in the shared services account is a best practice because it helps ensure that actions in the AWS accounts are logged. This action can be achieved with a service control policy (SCP) and a policy that explicitly denies CloudTrail configurations from being disabled. For example, see the following policy, which applies an explicit deny to any resource to prevent issuing either the StopLogging and DeleteTrail actions CloudTrail: { "Version": "2012-10-17", "Statement": [ { "Action": [ "cloudtrail:StopLogging", "cloudtrail:DeleteTrail" ], "Resource": "*", "Effect": "Deny"
> - Using MFA for users in centralized credentialing is a best practice because it helps ensure that users have multiple forms of authentication before they are granted access to AWS resources.   


#### 14. A solutions architect must create well-defined governance standards for a company that has multiple AWS accounts. The company needs centralized infrastructure logging for all AWS accounts. In addition, the company’s chief information security officer (CISO) would like to have a measurement that applies a circuit breaker to stop Amazon Elastic Compute Cloud (Amazon EC2) API activities if the billing alarms indicate suspicious activity. The company intends to use AWS Organizations. Which architectural scenario should the solutions architect propose to meet the company’s needs in the MOST effective way?
   - [x] Enable AWS CloudTrail for all accounts in AWS Organizations. Use Organizations to centralize all logs into one Amazon Simple Storage Service (Amazon S3) bucket. As the circuit breaker, use service control policies (SCPs) that have an explicit deny for Amazon EC2 API activity. These SCPs can then be applied to the root organizational unit (OU) as needed.
   - [ ] Enable AWS CloudTrail for all accounts in AWS Organizations. Use Organizations to centralize all logs into one Amazon Simple Storage Service (Amazon S3) bucket. Use multi-factor authentication (MFA) devices for every user in AWS IAM Identity Center (successor to AWS Single Sign-On).
   - [ ] Enable AWS CloudTrail for only the production accounts in AWS Organizations. Use Organizations to centralize logs into one Amazon Simple Storage Service (Amazon S3 bucket). For single sign-on, use AWS IAM Identity Center (successor to AWS Single Sign-ON).
   - [ ] Enable AWS CloudTrail for all accounts in AWS Organizations. Use Organizations to centralize logs in one Amazon Simple Storage Service (Amazon S3) bucket. As the circuit breaker, use AWS Identity and Access Management (IAM) policies on each account that have an explicit deny for Amazon EC2 API activity. The IAM policies can then be applied to the root organizational unit (OU) as needed.
> You can use AWS Organizations can consolidate all AWS CloudTrail logging into one account. For the circuit breaker, you can create an SCP that explicitly denies Amazon EC2 API calls. The SCP can then be applied at any level in the organizational structure by using AWS Organizations.  


--- 
> [Architecting Solutions on AWS](https://www.coursera.org/learn/architecting-solutions-on-aws/) {Week-4}

 
