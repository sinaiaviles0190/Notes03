# AWS Global Infrastructure
## Notes 03

### i. Key Points
- AWS Regions are regions where infrastructure is held. The closer you are to a region, the faster the service will be.
#### What are AWS Availability Zones (AZ) ?
- AZ is the building that makes up the AWS Region. Having multiple AZ's is beneficial, gives you more back up options just in case an instance fails and you have more resources to use.
- Endpoints are specific URLs that are entry points for a web service. Helps reduce the latency of applications
- Services that are related to each other will have an endpoint that mentions its geograhic location.
#### AWS Infrastructure Features
- Scalability and elastic: can adjust to changes in capacity requirements, much room for growth
- Fault tolerant: ability to continue operating even with failed components
- Minimal downtime, high availability 
#### Selecting the best region
- Make sure the services you want to use can be accesible in the region you are choosing
- Check compliance requirements (if any) and make sure AWS's compliance rules can run your work
- Check SLAs and cost, not the same in different regions
#### Foundational Services
- Compute: supports big data processing and research
  examples: EC2, EC2 Scaling, Elastic Container and Elastic Registry
- Storage: scalable, secure, reliable
  examples: Amazon S3 (Simple Storage Server), Elastic Block Store, Elastic File System
- Databases: use cases and provide speed, reliability, availibility
  examples: Amazon Relational Database Service (RDS), Amazon Aurora, Amazon Redshift
- Networking: preformance, global coverage, manageability, availibility
  examples: Amazon Private Cloud (VPC), Elastic Load Banding, CloudFront, Tranist Gateway
 

### ii. Quotes
- Section 5.07 mentions, " AWS has the largest global infrastructure footprint of any cloud provider in order to deliver customer’s content through a worldwide network.."
I found this interesting because AWS is much more widely used than I assumed. The fact that AWS tops Azure and Google Cloud is impressive.

### iii. New Information
- Data Security and Compliance: anything related to Health Care, Education, Bank & Finance 
- Most common data center in US is Northern Virginia
- One region contains multiple availability zones
- Edge locations: the data center used to deliver content to users
- within each availability zone there are multiple edge locations
- Number of availibility zones is greater than the number of regions
