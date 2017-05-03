![Certification Tracks](https://github.com/sairamaj/awssolutionarchitectexam/blob/master/images/certificationtracks.png)

# Cloud Computing
## Essentials
* On Demand
* Broad network access
* Resource pooling
* Rapid Elasticity 
* Measured services

## Service Models
* IaaS
* PaaS
* Saas

## Deployment Models
* Private (On Premises)
* Hybrid
* Community (ex: Gov cloud)
* Public    

## Key dates
* AWS 2002 July
* S3 March 2006
* EC2 Aug 2006
* Google App Engine 2008
* Azure Beta Nov -2009

## Regions
* Geographical location
## Availability Zones
* Data Centers within Regions
## Edge Locations
* Services to consume ( not to host services ( for ex: DNS - AWS Route 53))

## Ephemeral Storage (ephemeral means temporary)
* Instance store
* Temporary block-level storage
* Free storage with an EC2 instance
* Data is lost when instance is terminated or stopped
* There is no SLA, access speed is not guaranteed
* Buggers, caches, scratch data, etc...
* Replicate data for load-balanced web servers

## S3
* First AWS service introduced in 2006
* Internet accessible storage via HTTP/HTTPS
* Audit, video, images, backup etc.,
* Unlimited bucket size
* Up to 5 TB object size.
* Priced on storage used and transfer out
* It's not a file system
* Can host a static web site
* Replicated 3 times for high availability
* 2 types
  * Standard
  * Reduced Redundancy Storage(RRS) 

## EBS (Elast Block  storage)
* Not internet accessible
* Persistent file system for EC2
* Does not need to be attached to an instance.
* Can be transferred between AZ
* Supports incremental snapshots
* EBS leverages S# fo r snapshot storage

## Glacier
* Very cheap storage
* Useful for infrequently used data. Ideal for backup
* Very, very slow retrieval times ( 4- 6 hours)
* High durability
* Cost for restore
* AES 256 bit data encryption
 
## EC2
* Pay-per-use, scalable platform for VMs
* Supports Windows / Linux instances
* Amazon Machine Image(AMI) refers to a virtual disk template
* You can import/export your own AMIs (not amazon created AMIs because of license keys associated with those images)


## EC2 Compute Unit(ECU)
* A relative measure of processing power
* Abstract CPU hardware changes
* One ECU is equivalent to 1.0-1.2 GHZ 2007 Intel Opteron or 2007 Xeon
* Consistent amount of CPU capacity regardless of hardware
* Each instance type may be used on different physical processors
* Manage consistency through benchmarks and tests


## EC2 Instance types
* Micro instances
* General purpose
* CPU Optimized
* GPU instances
* Memory Optimized
* Storage Optimized

## [EC2 pricing](http://aws.amazon.com/ec2/pricing)
* OnDemand
  * The default type
  * The most expensive option
  * No commitment
  * Price vary by AWS regions
  * Billed on hourly basis (ex: 20mins usage means 1 hour charge)

* Reserved Instance
  * Less expensive
  * Required commitment of 1 or 3 years
  * Has an upfront const
  * Lower hourly rate
  * RI can be sold on AWS Market place
  * you commit to utilization
    * Light utilization
    * Medium utilization
    * Heavy utilization ( 100 % running)
* Spot instances
  * Unused AWS capacity
  * Very cheap hourly rate
  * Not guaranteed
  * Based on bid
  * Ideal for raw-processing power, grid-like applications
  * Highly scriptable

* Misc pricing

[Cost estimator](http://url here)

![AWS terminology](https://github.com/sairamaj/awssolutionarchitectexam/blob/master/images/awsterminology.png)

[AWS Info](http://cdn.awsnow.info/)

## Elastic Load Balancing (ELB)
* Region wide load balancer
* Can be used internally or externally
* SSL termination and processing
* ELB EC2 health check
* Router 53 performs ELB health checks

## Route 53
* DNS is crucial for any environment
* World wide distributed DNS
* 100% SLA
* Route 53 API
* Server health checks

## AWS Cloud watch
* Basic Monitoring
* Detailed Monitoring
* Set alarms and alerts
* Notifications via SES,SNS
* Custom Monitoring through API
* Integrate with Auto scaling
* Mobile app for basic monitoring and management

## Auto scaling
* Expand or shrink instances on-demand
* Cloudwatch or manual schedule configuration
* Notifications


## SES (Simple Email Service)
* Cost effective bulk email service 
* Cost based on number of emails sent
* Outbound-only email-sending service
* Leverages Amazon email reputation
* Initially limited to 10,000 emails/day

## SQS (Simple Queue Service)
* Fast, Reliable and scalable
* Unlimited messages and queue size
* Payload up to 256KB
* Billed in chunks of 64KB payloads
* First milliion requests are Free
* $0.50/milliion SQS requests

## SNS(  Simple Notification Service)
* Push messaging service
* HTTP/HTTPS
* Email
* Email-Json
* SMS
* Amazon SQS queues

## CloudFront
* Global content delivery network
* Leverages all AWS edge locations
* Cache static content
* Proxy dynamic information
* Work with AWS and non-AWS services

## CloudFormation
* Automate AWS resource provisioning
* Free service
* Deleting the cloudformation deletes all instances except data

## Elastic Beanstalk
* More for developers
* Node.JS
* Ruby
* PHP
* Python
* IIS
* Tomcat

## CloudTrail
* Records all API calls
* Log file includes: (Identity api caller, Time, source ip, etc,)
* Maintain history



