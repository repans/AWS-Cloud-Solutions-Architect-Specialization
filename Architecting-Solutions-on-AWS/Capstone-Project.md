```
  # Do not copy if you are taking the test.
```
--- 

# Capstone Project

It’s time to put together everything you learned!

As part of this project, you will create a high-level architecture diagram that uses 
[AWS service icons and arrows](https://aws.amazon.com/architecture/icons/) 
to depict an AWS solution for the given scenario. Create your diagram by using a tool like
[diagrams.net](https://app.diagrams.net/?splash=0&libs=aws4) 
, or you can select a different tool by from the
[AWS Architecture Icons](https://aws.amazon.com/architecture/icons/) 
page by scrolling to the Drawing and diagramming tools section.

**Scenario:** You are working for a customer that runs their workloads on premises. Your customer has two workloads:
- A three-tier architecture composed of a frontend (HTML, CSS, JavaScript), backend (Apache Web Server and a Java application), and database (MySQL). The three-tier application hosts a dynamic website that accepts user traffic from the internet.
- A data analytics workload that runs Apache Hadoop. The analytics workload analyzes a massive amount of data that stored on premises and it also uses visualization tools to derive insights.
These components are currently running in the data center on physical servers. Currently, if a power outage occurred in the data center, all systems would be brought offline. Because of this issue (in addition to other benefits of the cloud), your customer wants to migrate all components to the cloud and, when possible, use AWS services to replace on-premises components.

**Instructions:** You have been tasked with designing a solution that uses AWS services to decouple the application layers (frontend, backend, and database), and that hosts both the application and the data analytics workload in the cloud. You can use managed services and advocate for refactoring the code to take advantage of cloud-native technologies, or you can do a lift and shift and advocate for minimal refactoring. Also, the data analytics solution currently runs on Hadoop and you have a requirement to spin up an Amazon EMR cluster for it. However, it’s up to you to choose which AWS services you want to use for the ingestion, storage, and visualization of data.
Whichever architecture you choose to create, think about how the solution works and why you chose to use the services that you selected. Also, create an architecture diagram that depicts how both solutions will be hosted on AWS. 


--- 
> [Architecting Solutions on AWS](https://www.coursera.org/learn/architecting-solutions-on-aws/) {Week-4}

 
