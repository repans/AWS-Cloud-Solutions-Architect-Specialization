```
  # Do not copy if you are taking the test.
```
--- 

# Week 2 Assessment


#### 01. A solutions architect is designing an architecture that can provide HTML pages to customers. They want a serverless solution that can host content over the internet and serve a static website with minimal effort. Which AWS service should the solutions architect choose to meet these requirements?
   - [x] Amazon Simple Storage Service (Amazon S3)
   - [ ] Amazon Elastic Compute Cloud (Amazon EC2)
   - [ ] Amazon DynamoDB
   - [ ] Amazon Kinesis
> You can use Amazon S3 to host a static website. On a static website, individual webpages include static content. They might also contain client-side scripts. By contrast, a dynamic website relies on server-side processing, which can include server-side scripts that are written in PHP, JSP, or ASP.NET. Amazon S3 does not support server-side scripting, but AWS has other resources for hosting dynamic websites. To learn more about website hosting on AWS, see Web Hosting (https://aws.amazon.com/websites/).


#### 02. A solutions architect is designing a solution that needs real-time data ingestion. They are considering either Amazon Kinesis Data Firehose or Amazon Kinesis Data Streams for this solution. Which service should the solutions architect choose to meet the requirement for real-time data ingestion, and why? (Remember that lower data latency means a lower roundtrip time from when data is ingested and available.)
   - [ ] Amazon Kinesis Data Firehose, because it has lower latency when compared to Amazon Kinesis Data Streams
   - [ ] Amazon Kinesis Data Firehose, because it has higher latency when compared to Amazon Kinesis Data Streams
   - [x] Amazon Kinesis Data Streams, because it has lower latency when compared to Amazon Kinesis Data Firehose
   - [ ] Amazon Kinesis Data Streams, because it has higher latency when compared to Amazon Kinesis Data Firehose
> Amazon Kinesis Data Streams is suitable for low-latency data streaming, which makes it more suitable for real-time analytics instead of a service like Amazon Kinesis Data Firehose.  


#### 03. True or False: When creating data lakes for analytics on AWS, Amazon Simple Storage Service (Amazon S3) would be a preferred service. Users can use data in an S3 bucket with an independent data-processing or visualization layer, such as Amazon QuickSight, Amazon Athena, or Amazon EMR.
   - [x] True
   - [ ] False
> Amazon S3 provides storage capabilities without charging for data processing. You can use additional services to get data from Amazon S3 and process it. For example, you could use the services that were mentioned in the question, or you could use any other AWS service that can GET or PUT data in Amazon S3 through the S3 API operations. 


#### 04. A solutions architect is designing a serverless solution that can do Structured Query Language (SQL) queries over multiple objects that are stored in Amazon Simple Storage Service (Amazon S3). All the objects share the same data structure (schema) and are in JSON. Which service would make it easier to query the data, in addition to providing serverless capabilities?
   - [x] Amazon Athena
   - [ ] AWS Database Migration Service (AWS DMS)
   - [ ] Amazon S3 Select
   - [ ] AWS Data Exchange
> Amazon Athena is an interactive query service that makes it easier to analyze data in Amazon S3 by using standard SQL. Athena is serverless. There is no infrastructure to manage, and you pay only for the queries that you run. Athena is straightforward to use: point to the data in Amazon S3, define the schema, and query with standard SQL. 


#### 05. True or False: When architecting a solution that can handle high demand and usage spikes, Amazon CloudFront should be used in front of an Amazon Simple Storage Service (Amazon S3) bucket. CloudFront can cache data that gets delivered to customers, and it lets customers use custom domain names. In addition, CloudFront can serve custom SSL certificates that are issued by Amazon Certificate Manager (at no additional cost) and it can provide distributed denial of service (DDoS) protection that is powered by AWS WAF and AWS Shield.
   - [x] True
   - [ ] False
> CloudFront is a web service that speeds up the distribution of static and dynamic web content (such as .html, .css, .js, and image files) to users. CloudFront delivers content through a worldwide network of data centers that are called edge locations. CloudFront is designed to use edge locations to deliver content with the best possible performance. When a user requests content that is served through CloudFront, the request is routed to the edge location that provides the lowest latency (time delay).


--- 
> [Architecting Solutions on AWS](https://www.coursera.org/learn/architecting-solutions-on-aws/) {Week-2}

 
