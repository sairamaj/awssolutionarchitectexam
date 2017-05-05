## Root User
* All AWS accounts have a root user
* Full access to all AWS services and resources
* Permissions cannot be restricted
* Root user should be protected like a credit card number or any critical information
* Principle of least privilege should be followed when delegating permissions

## IAM User features
* Shared access to AWS account
* Granular permissions
* Secure access for apps on EC2
* Identity federation
* Identity information for assurance
* Integrated with many AWS features and free
* Can define who has access to __which__ resource from __where__ and __when__
* Support multi factor authentication and auditing
* Password policies applies to all accounts
* Access keys are used in place of username and passwords
* Maximum 2 keys per user
* Rotate access keys periodically
* Remove unused access keys
* Use AWS credential file  or environment variables rather than hard coding access keys

## Configuring with access key
* aws configure
 * AWS Access Key ID:
 * AWS Secret Access Key:
 * Default region:
 * Default output format:

## MFA Options
* Hardware
* Virtual (software - Google Authenticator etc.,)
* SMS text based

## Policy
* Policy is a document that lists the actions a user can perform and the resources that the action affect
* Version and can be rolled back

### Managed Policy
* AWS Managed
  * You get policies added by AWS automatically (like any other new services added to existing policy)
* Customer Managed
  * Any new services one has to take care of
  * More control
### In line Policy
* Cannot be shared ( not reusable).


### Example
```json
{
   "Version": "2013-11-18",
   "Statement" :{
       "Effect": "Allow",
       "Action":  dynamodb:*,
       "Resource": "arn:aws:dynamodb:us-west 2:124:tables/Sales"
   }
}
```

## Access Control
* Who ( bob)
* Effect (is allowed)
* Action (to work with dynamodb)
* What (only sales table)
* Conditions (If authenticated us ing MFA
)

## Policy Simulator
* allows testing the policies
* Hypothetical service request (no actual action)
* Cannot report any responses (only reports on an Allow or deny )
* Worry-free policy editing
* https://policysim.aws.amazon.com

## Roles
* Set of permissions
* Permissions are assigned to roles, not users
* Can be assumed by users, web services, or a federated user
* Helps in Single signon
* Provide temporary credentials for granting access to applications and services
* Federate with existing and external identity providers
* Provides basis for cross-account access

## Delegation
* Assigning privileges to other people on resources you own
* Required setting up trust between AWS accounts
* Delegation can be done within the same AWS account, between accounts owned by the same organization, or between accounts owned by different organizations
* Delegating permissions to AWS resources to users belonging to external identity sources (ex: Google , Facebook accounts)
