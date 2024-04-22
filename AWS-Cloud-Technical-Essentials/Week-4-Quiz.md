```
  # Do not copy if you are taking the test.
```
--- 

# Week 4 Quiz


### 01. What are the three components of Amazon EC2 Auto Scaling?
   - [ ] Scaling policies, security group, EC2 Auto Scaling group
   - [x] Launch template, scaling policies, EC2 Auto Scaling group
   - [ ] Security group, instance type, key pair
   - [ ] Amazon Machine Image (AMI) ID, instance type, storage
> Amazon EC2 Auto Scaling requires users to specify three main components: a configuration template for the Amazon Elastic Compute Cloud (Amazon EC2) instances (either a launch template or a launch configuration); an EC2 Auto Scaling group to list minimum, maximum, and desired capacity of instances; and scaling policies that scale an instance based on the occurrence of specified conditions or on a schedule. For more information, see Amazon EC2 Auto Scaling.

### 02. Which of the following features are included in Elastic Load Balancing (ELB)?
   - [ ] Automatic scaling
   - [ ] Integration with Amazon Relational Database Service RDS
   - [ ] Integration with Amazon EC2 Auto Scaling
   - [ ] A and B
   - [x] A and C
> ELB automatically distributes incoming traffic across multiple targets—such as Amazon Elastic Compute Cloud (Amazon EC2) instances, containers, and IP addresses—in one or more Availability Zones. ELB automatically scales its capacity in response to changes in incoming traffic. In addition, if users enable Auto Scaling with Elastic Load Balancing, instances that are launched by Auto Scaling are automatically registered with the load balancer. For more information, see Route Traffic with Amazon Elastic Load Balancing.

### 03. True or False: When a user uses Elastic Load Balancing (ELB) with an Auto Scaling group, it is not necessary to manually register individual Amazon Elastic Compute Cloud (Amazon EC2) instances with the load balancer.
   - [x] True
   - [ ] False
> The load balancer automatically registers new instances. For more information, see Amazon EC2 Auto Scaling.

### 04. An application must choose target groups by using a rule that is based on the path of a URL. Which Elastic Load Balancing (ELB) type should be used for this use case?
   - [ ] Classic Load Balancer
   - [x] Application Load Balancer
   - [ ] Network Load Balancer
   - [ ] Target Load Balancer
> Application Load Balancer is a layer 7 load balancer that routes HTTP and HTTPs traffic, with support for rules. For more information, see Route Traffic with Amazon Elastic Load Balancing.

### 05. What are the two ways that an application can be scaled?
   - [x] Vertically and horizontally
   - [ ] Diagonally and vertically
   - [ ] Horizontally and diagonally
   - [ ] Independently and vertically
> An application can be scaled vertically by adding more power to an existing machine, or it can be scaled horizontally by adding more machines to a pool of resources. For more information, see Optimizing Solutions on AWS.

### 06. Which elements in Amazon CloudWatch dashboards can be used to view and analyze metrics?
   - [x] Widgets
   - [ ] Metrics
   - [ ] Icons
   - [ ] Components
> Widgets are the elements that can be added to a dashboard. For more information, see the Introduction to Amazon CloudWatch video.

### 07. What are the possible states of a metric alarm in Amazon CloudWatch?
   - [ ] OK, ALARM, NOT_AVAILABLE
   - [ ] OK, ALERT, INSUFFICIENT_DATA
   - [x] OK, ALARM, INSUFFICIENT_DATA
   - [ ] OK, ALERT, NOT_AVAILABLE
> A metric alarm in CloudWatch has the following possible states. OK: The metric or expression is within the defined threshold. ALARM: The metric or expression is outside of the defined threshold. INSUFFICIENT_DATA: For this state, the alarm has just started, the metric is not available, or not enough data is available for the metric to determine the alarm state. For more information, see the Introduction to Amazon CloudWatch video.

### 08. What kind of data can a company collect with VPC Flow Logs?
   - [x] Data about network traffic that comes into and out of a virtual private cloud (VPC)
   - [ ] Malicious activity and unauthorized behavior
   - [ ] Configurations of AWS resources
   - [ ] Compliance-related information
> With VPC Flow Logs, a company can collect data about network traffic that comes into and out of their VPC. For more information, see Monitoring on AWS.

### 09. What is a benefit of monitoring on AWS?
   - [ ] Monitoring creates operation overhead.
   - [x] Monitoring recognizes security threats and events.
   - [ ] Monitoring decreases the performance and reliability of resources.
   - [ ] Monitoring increases speed and agility
> When users monitor resources, events, and systems over time, they create what is called a baseline. A baseline defines what activity is normal. By using a baseline, users can spot anomalies, such as unusual traffic spikes or unusual IP addresses that are accessing resources. When an anomaly occurs, an alert can be sent or an action can be taken to investigate the event. For more information, see Reading: Monitoring on AWS.

### 10. True or False: When a company redesigns an application by using a serverless service on AWS, they might not need to configure networking components, such as a virtual private cloud (VPC), subnets, and security groups.
   - [x] True
   - [ ] False
> By default, AWS Lambda runs functions in a secure VPC with access to AWS services and the internet. For more information, see Redesigning the Employee Directory Application.




--- 
> [AWS Cloud Technical Essentials](https://www.coursera.org/learn/aws-cloud-technical-essentials/) {Week-4}
