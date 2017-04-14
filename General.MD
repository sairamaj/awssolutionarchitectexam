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

## ECB
* Not internet accessible
* Persistent file system for EC2
* Does not need to be attached to an instance.
* Can be transferred between AZ
* Supports incremental snapshots
* EBS leverages S# for snapshot storage

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

![AWS terminology](https://github.com/sairamaj/awssolutionarchitectexam/blob/master/images/awsterminology.png)