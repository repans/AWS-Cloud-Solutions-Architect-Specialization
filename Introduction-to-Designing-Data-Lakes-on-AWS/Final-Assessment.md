```
  *** Do not copy if you are taking the test. ***
```
--- 

# Final Assessment 


#### 01. What does the AWS Glue Metadata Catalog service do?
  
- [ ] The AWS Glue Metadata Catalog is a query service that uses standard Structured Query Language (SQL) to retrieve data.  
- [ ] The AWS Glue Metadata Catalog provides a data transformation service where a company can author and run scripts to transform data between data sources and targets.  
- [ ] The AWS Glue Metadata Catalog provides a repository where a company can store and find metadata to keep track of user permissions to data in a data lake.  
- [x] The AWS Glue Metadata Catalog provides a repository where a company can store, find, and access metadata, and use that metadata to query and transform the data.


#### 02. A solutions architect is working for a customer who wants to build a data lake on AWS to store different types of raw data. Which AWS service should the solutions architect recommend to the customer to meet their requirements?
  
- [ ] AWS Glue Metadata Catalog  
- [ ] Amazon OpenSearch Service  
- [ ] Amazon EMR  
- [x] Amazon Simple Storage Service (Amazon S3)

#### 03. Which statement BEST describes batch data ingestion?
  
- [ ] By using batch data ingestion, a user can create a unified metadata repository across various services on AWS.  
- [ ] Batch data ingestion is the process of capturing gigabytes (GB) of data per second from multiple sources, such as website clickstreams, database event streams, financial transactions, social media feeds, IT logs, and location-tracking events.   
- [x] Batch data ingestion is the process of collecting and transferring large amounts of data that have already been produced and stored on premises or in the cloud.  
- [ ] Batch data ingestion is a serverless data integration service that makes it easier to discover, prepare, and combine data for analytics, machine learning, and application development. 

#### 04. Which service is commonly used for real-time data processing when Amazon Kinesis Data Streams is used for data ingestion?
  
- [ ] AWS Glue job  
- [x] Amazon Kinesis Data Analytics  
- [ ] Amazon EMR  
- [ ] Amazon Athena


#### 05. Apache Hadoop is an open-source framework that is used to efficiently store and process large datasets. A solutions architect is working for a company that currently uses Apache Hadoop on-premises for data processing jobs. The company wants to use AWS for these jobs, but they also want to continue using the same technology. Which service should the solutions architect choose for this use case?
  
- [x] Amazon EMR  
- [ ] Amazon OpenSearch Service  
- [ ] Amazon Kinesis Data Analytics  
- [ ] AWS Lambda


#### 06. A team of machine learning (ML) experts are working for a company. The company wants to use the data in their data lake to train an ML model that they create. The company wants the most control that they can have over this model and the environment that it is trained in. Which AWS ML approach should the team take?
  
- [ ] Use a pretrained model from an AWS service, such as Amazon Rekognition.  
- [x] Launch an Amazon Elastic Compute Cloud (Amazon EC2) instance by using an AWS Deep Learning Amazon Machine Image (AMI) to host the application that will train the model.  
- [ ] Create an AWS Lambda function with the training logic in the handler, and run the training based on an event.  
- [ ] Launch an Amazon Elastic Compute Cloud (Amazon EC2) instance and run Amazon SageMaker on it to train the model.


#### 07. What is the main value proposition of data lakes?
  
- [ ] The ability to define the data schema before ingesting and storing data.  
- [ ] The ability to combine multiple databases together to expand their capacity and availability.  
- [x] The ability to ingest and store data that could be the answer for future questions when they are processed with the correct data processing mechanisms.  
- [ ] The ability to store user-generated data, such as data from antennas and sensors.

#### 08. Which statements about data lakes and data warehouses are true? (Choose TWO.)
  
- [ ] Data lakes use schema-on-write architectures and data warehouses use schema-on-read architectures.  
- [x] Data lakes offer more choices in terms of the technology that is used for processing data. In contrast, data warehouses are more restricted to using Structured Query Language (SQL) as the query technology.  
- [x] The solutions architect can combine both data lakes and data warehouses to better extract insights and turn data into information.  
- [ ] The solutions architect cannot attach data visualization tools to data warehouses.  
- [ ] Data lakes are not future-proof, which means that they must be reconfigured each time new data is ingested.

#### 09. A company plans to explore data lakes and their components. What are reasons to invest in a data lake? (Choose TWO.)
  
- [x] Offload capacity from databases and data warehouses  
- [ ] Increase operational overhead  
- [ ] Limit data movement  
- [ ] Make data available from integrated departments  
- [x] Lower transactional costs


#### 10. Which term indicates that a data lake lacks curation, management, cataloging, lifecycle or retention policies, and metadata?
  
- [x] Data swamp  
- [ ] Data warehouse  
- [ ] Data catalog  
- [ ] Database


#### 11. Which statement about whether data lakes make it easier to follow the “right tool for the job” approach is TRUE?
  
- [ ] Yes, data lakes make it easier to follow “the right tool for the job” approach because data lakes can only handle structured data.  
- [ ] No, data lakes do not make it easier to follow “the right tool for the job approach” because data lakes can only handle structured data.  
- [ ] No, data lakes do not make it easier to follow “the right tool for the job approach” because you are tied to a specific AWS service.  
- [x] Yes, data lakes make it easier to follow “the right tool for the job” approach because storage can be decoupled from processing and ingestion.


#### 12. Which scenario represents AWS Glue jobs as the BEST tool for the job?
  
- [ ] Analyze data in real time as data comes into the data lake.  
- [ ] Transform data in real time as data comes into the data lake.  
- [ ] Analyze data in batches on schedule or on demand.  
- [x] Transform data on a schedule or on demand.


#### 13. Which task is performed by an AWS Glue crawler?
  
- [ ] Analyze all data in the data lake to create an Apache Hive metastore.  
- [ ] Store metadata in a catalog for indexing.  
- [x] Populate the AWS Glue Data Catalog with tables.  
- [ ] Map data from one schema to another schema.


#### 14. A software developer recently uploaded data logs from their application to Amazon Simple Storage Service (Amazon S3). Who is responsible for encrypting both the data at rest in the S3 bucket and the data in transit to the S3 bucket, according to the AWS shared responsibility model?
  
- [ ] AWS  
- [x] Customer  
- [ ] Both AWS and the customer  
- [ ] Third-party security company


#### 15. What makes Amazon QuickSight different, compared to other traditional business intelligence (BI) tools?
  
- [x] Super-fast, Parallel, In-memory Calculation Engine (SPICE)  
- [ ] The ability to create sharable dashboards  
- [ ] The ability to visualize data  
- [ ] Data encryption at every layer


#### 16. What is the purpose of the Registry of Open Data on AWS? 
  
- [ ] Provide a service that people can use to ingest software as a service (SaaS) application data into a data lake.  
- [x] Help people discover and share datasets that are available through AWS resources.  
- [ ] Provide a service that people can use to transform public datasets that are published by data providers through an API.   
- [ ] Help people discover and share datasets that are available outside of AWS resources.


#### 17. Which statements about data organization and categorization in data lakes are TRUE? (Choose TWO.)
  
- [ ] Data lakes need to be schema-on-write. In this case, users need to transform all the data before they load it into the data lake.  
- [ ] Data lakes are not future-proof, which means that they must be reconfigured each time new data is ingested.  
- [ ] Users must delete the original raw data to keep their data lake organized and cataloged.  
- [x] When cataloging data, it is a best practice to organize the data according to the access pattern of the user who will access it.  
- [x] Amazon Simple Storage Service (Amazon S3) is mostly used for storage, and AWS Glue is mostly used for categorizing data.


#### 18. Which type of data has the HIGHEST probability of containing structured data?
  
- [ ] Customer reviews on products in retailer websites  
- [ ] Raw data from marketing research surveys  
- [ ] Video files from mobile phone photo libraries  
- [x] Data that is sitting in a relational MySQL table

#### 19. What is the most common way of categorizing data in terms of structure?
  
- [ ] The good data, the bad data, and the ugly data  
- [ ] Development data, quality assurance (QA) data, and production data  
- [x] Structured data, unstructured data, and semi-structured data  
- [ ] Ready data, not-ready data, and semi-ready data

#### 20. Which statement about data consumption in Amazon Kinesis Data Streams is TRUE?
  
- [ ] If data is consumed by a consumer, that consumer can never get that same data again. This case is true even if the data is still in the stream, according to the data-retention window.  
- [ ] If data is not consumed within 15 minutes, Kinesis will delete the data that was added to the stream. This case is true even though the data-retention window is greater than 15 minutes.  
- [ ] Data is automatically pushed to each consumer that is connected to Kinesis. Thus, consumers are notified that new data is available, even when they are not running the Kinesis SDK for data consumption.  
- [x] Data consumers must use an AWS SDK to correctly fetch data from Kinesis in the same order that it was ingested. However, AWS Lambda functions do not need to fetch data from Kinesis in a specific order because Lambda integrates natively with AWS services, including Kinesis.



--- 
> [Introduction to Designing Data Lakes on AWS](https://www.coursera.org/learn/introduction-to-designing-data-lakes-in-aws/) {Week-4}
