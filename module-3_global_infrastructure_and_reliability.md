# Module 3 - Infrastructure

## "A Region consists of two or more Availability Zones."

### Amazon CloudFront (It's a CDN)
- A global content delivery service
- Uses edge locations for low latency content delivery
- Edge locations are separate from regions
- Also uses Amazon Route 53 for DNS

### AWS Outposts
- AWS Mini-region in private data center

### Provisioning AWS Resources:
- AWS Management Console
- CLI
- SDKs
- AWS Elastic Beanstalk
- AWS CloudFormation

### AWS Elastic Beanstalk:
- Build and save infrastructure deployment configs easily

### AWS CloudFormation:
- Infrastructure as code
- CloudFormation templates in json or yml
- CloudFormation Engine will make API calls to build the infrastructure
