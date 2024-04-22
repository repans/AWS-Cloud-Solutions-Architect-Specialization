```
  # Do not copy if you are taking the test.
```
--- 

# Week 1 Quiz

### 01. What are the four main factors that a solutions architect should consider when they must choose a Region?

- [x] Latency, price, service availability, and compliance  
- [ ] Latency, high availability, taxes, and compliance
- [ ] Latency, taxes, speed, and compliance   
- [ ] Latency, security, high availability, and resiliency   

> A solutions architect should consider the following four aspects when deciding which AWS Region to use for hosting applications and workloads: latency, price, service availability, and compliance. For more information, see the AWS Global Infrastructure video in week 1.


### 02. True or False: Every action a user takes in AWS is an API call.
   
- [x] True   
- [ ] False

> In AWS, every action a user takes is an API call that is authenticated and authorized. A user can make API calls through the AWS Management Console, the AWS Command Line Interface (AWS CLI), or the AWS SDKs. For more information, see the Interacting with AWS video.


### 03. Which statement BEST describes the relationship between Regions, Availability Zones and data centers?
   
- [ ] Availability Zones are clusters of Regions. Regions are clusters of data centers.   
- [ ] Data centers are cluster of Availability Zones. Regions are clusters of Availability Zones.   
- [x] Regions are clusters of Availability Zones. Availability Zones are clusters of data centers.   
- [ ] Data centers are clusters of Regions. Regions are clusters of Availability Zones.

> The AWS Cloud infrastructure is built around AWS Regions and Availability Zones. An AWS Region is a physical location in the world that has multiple Availability Zones. Availability Zones consist of one or more discrete data centers, each with redundant power, networking, and connectivity, housed in separate facilities. For more information, see the AWS Global Infrastructure video in week 1.


### 04. Which of the following is a benefit of cloud computing?
   
- [ ] Run and maintain your own data centers.   
- [ ] Increase time-to-market.   
- [ ] Overprovision for scale.   
- [x] Go global in minutes.

> Going global in minutes means that users can easily deploy applications in multiple Regions around the world with a few clicks. For more information, see the What is AWS reading.


### 05. A company wants to manage AWS services by using the command line and automating them with scripts. What should the company use to accomplish this goal?
   
- [ ] AWS Management Console   
- [x] AWS Command Line Interface (AWS CLI)   
- [ ] AWS SDKs
- [ ] AWS Management Console and AWS SDKs

> The AWS CLI is a unified tool that is used to manage AWS services. By downloading and configuring the AWS CLI, the company can control multiple AWS services from the command line and automate them with scripts. For more information about the correct answer, see the Interacting with AWS reading.


### 06. What is a best practice when securing the AWS account root user?
   
- [ ] Activate AWS Identity and Access Management (IAM) access to the Billing and Cost Management console   
- [ ] Use the root user for routine administrative tasks   
- [ ] Change account settings   
- [x] Enable multi-factor authentication

> It is important to not use the AWS account root user access key to sign in to the AWS account. The access key for an AWS account root user gives full access to all resources for all AWS services, including billing information. Users cannot reduce the permissions that are associated with their AWS account root user access key. Users must delete any access keys that are associated with the root user and enable multi-factor authentication (MFA) for the root user account. For more information, see the Protect the AWS Root User reading.


### 07. A solutions architect is consulting for a company. When users in the company authenticate to a corporate network, they want to be able to use AWS without needing to sign in again. Which AWS identity should the solutions architect recommend for this use case?
   
- [ ] AWS account root user   
- [ ] AWS Identity and Access Management (IAM) user   
- [x] IAM Role   
- [ ] IAM Group

> An IAM role does not have any credentials (password or access keys) that are associated with it. Instead of being uniquely associated with one person, a role can be assumed by anyone who needs it. An IAM user can assume a role to temporarily take on different permissions for a specific task. A role can be also assigned to a federated user who signs in by using an external identity provider (IdP) instead of IAM. For more information, see the Role Based Access in AWS video.


### 08. Which of the following can be found in an AWS Identity and Access Management (IAM) policy?
   
- [ ] Effect   
- [ ] Action   
- [ ] Object   
- [x] A and B   
- [ ] B and C

> An IAM policy contains a series of elements, including a Version, Statement, Sid, Effect, Principal, Action, Resource, and Condition. For more information, see Introduction to Amazon Identity and Access Management.


### 09. True or False: AWS Identity and Access Management (IAM) policies can restrict the actions of the AWS account root user.
   
- [ ] True   
- [x] False

> The account root user has complete access to all AWS services and resources in an account, as well as billing and personal information. Because of this, we recommend that you securely lock away the credentials that are associated with the root user, and not to use the root user for everyday tasks. For more information, see the Protect the AWS Root User reading.


### 10. According to the AWS shared responsibility model, which of the following is the responsibility of AWS?
   
- [ ] Controlling the operating system and application platform, as well as encrypting, protecting, and managing customer data.   
- [ ] Managing customer data, encrypting that data, and protecting the data through network firewalls and backups.   
- [x] Managing the hardware, software, and networking components that run AWS services, such as the physical servers, host operating systems, virtualization layers, and AWS networking components.   
- [ ] Managing customer data, encrypting that data, and protecting the data through client-side encryption.

> AWS is responsible for protecting and securing AWS Regions, Availability Zones, and data centers, down to the physical security of the buildings, as well as managing the hardware, software, and networking components that run AWS services.


### 11. Which of the following is recommended if a company has a single AWS account, and multiple people who work with AWS services in that account?
   
- [ ] All people must use the root user to work with AWS services on a daily basis.   
- [x] The company should create an AWS Identity and Access Management (IAM) group, grant the group permissions to perform specific job functions, and assign users to a group, or use IAM roles.   
- [ ] The company must create AWS Identity and Access Management (IAM) users, and grant users the permissions to perform specific job functions.   
- [ ] The company must create an AWS Identity and Access Management (IAM) user and grant the user the permissions to access all AWS resources.

> With IAM, a company can create an IAM user group, grant the user group the permissions to perform specific job functions, and assign users to a group. This way, the company provides granular access to its employees, and people and services have permissions to only the resources that they need. The company could also achieve the same purpose by using IAM roles for federated access and using granular policies that are attached to roles. For more information, see Reading: Introduction to AWS Identity and Access Management.


### 12. True or False: According to the AWS shared responsibility model, a customer is responsible for security in the cloud.
   
- [x] True   
- [ ] False

> A customer is responsible for security in the cloud, while AWS is responsible for security of the cloud. For more information, see the Security and the AWS Shared Responsibility video.


### 13. Which of the following provides temporary credentials (that expire after a defined period of time) to AWS services?
   
- [ ] Principle of least privilege   
- [x] IAM role   
- [ ] Identity provider (IdP)   
- [ ] AWS IAM Identity Center (successor to AWS Single Sign-On)

> When a user assumes a role, AWS Identity and Access Management (IAM) dynamically provides temporary credentials that expire after a defined period of time, between 15 minutes and 36 hours. For more information, see Reading: Role Based Access in AWS.


### 14. A user is hosting a solution on Amazon Elastic Compute Cloud (Amazon EC2). Which networking component is needed to create a private network for their AWS resources?
   
- [x] Virtual private cloud (VPC)   
- [ ] Instance   
- [ ] Tags   
- [ ] Amazon Machine Image (AMI)

> A VPC is a private network for AWS resources. For more information, see Hosting the Employee Directory Application on AWS.


--- 
> [AWS Cloud Technical Essentials](https://www.coursera.org/learn/aws-cloud-technical-essentials/) {Week-1}
