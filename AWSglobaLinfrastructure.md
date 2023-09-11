# AWS Global Infrastructure
## Notes 03

### i. Key Points
- AWS Regions are regions where infrastructure is held. The closer you are to a region, the faster the service will be.
- Important to keep Service Level Agreement (SLA) in mind, for it will vary depending on the region, as will cost. 
#### What are AWS Availability Zones (AZ) ?
- AZ is the building that makes up the AWS Region. Having multiple AZ's is beneficial, gives you more back up options just in case an instance fails and you have more resources to use.
- Endpoints are specific URLs that are entry points for a web service. Helps reduce the latency of applications
- Services that are related to each other will have an endpoint that mentions its geograhic location.
#### AWS Infrastructure Features
- Scalability and elastic: can adjust to changes in capacity requirements, much room for growth
- Fault tolerant: ability to continue operating even with failed components
- Minimal downtime, high availability 
