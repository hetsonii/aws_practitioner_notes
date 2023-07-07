# Module 5 - Storage and Databases

### Amazon Elastic Block Store (EBS):
- Block storage - only the pieces that are changed are updated
- Not serverless
- No autoscaling
- Stored on a single availability zone

### Amazon Simple Storage Service (Amazon S3):
- Object Storage - When a file is modified, the entire object is updated.
- Serverless

### Amazon S3 classes:
- S3 Standard:
  - High availability - stores data on a minimum of 3 availability zones
  - Higher cost

- S3 Standard - Infrequent Access (S3 Standard-IA):
  - Similar to Amazon S3 Standard but has a lower storage price and higher retrieval price
  - High availability - stores data in a minimum of 3 Availability Zones.

- S3 One Zone - Infrequent Access (S3 One Zone-IA):
  - Stores data in a single Availability Zone
  - Has a lower storage price than Amazon S3 Standard-IA

- S3 Intelligent-Tiering:
  - Ideal for data with unknown or changing access patterns
  - Requires a small monthly monitoring and automation fee per object

- S3 Glacier Instant Retrieval:
  - Works well for archived data that requires immediate access
  - Can retrieve objects within a few milliseconds

- S3 Glacier Deep Archive:
  - Lowest-cost object storage class ideal for archiving
  - Able to retrieve objects within 12 hours

- S3 Outposts:
  - Creates S3 buckets on Amazon S3 Outposts (on-prem apps)

### Amazon Elastic File System (EFS):
- Linux File System
- Multiple instances reading/writing simultaneously
- Regional Resource (multiple availability zones)
- Autoscaling

### Amazon Relational Database Service (RDS):
- Lift and shift migration (from on-prem to AWS)
- Uses Amazon EBS volumes for database and log storage.
- No autoscaling
- Recovery provided
- Customer ownership of data, schema, and network

### Amazon Aurora:
- Continuous backup to Amazon S3
- Point-in-time Recovery.
- Replicates 6 copies of your data across 3 Availability Zones.

### Amazon DynamoDB:
- Serverless database
- Highly autoscalable
- High performance
- Non-relational, NoSQL db
- Granular API access

### Amazon Redshift:
- Data warehousing as a service

### Amazon Database Migration Service (DMS):
- Homogeneous and heterogeneous migrations
- Use cases:
  - Development and test db migrations
  - Database consolidation
  - Continuous replication

### Additional database services:
- DocumentDB [Supports MongoDB workloads]
- Neptune [Graph database that works with highly connected datasets]
- Quantum Ledger Database (QLDB) [Immutable. Can review a complete history of all the changes in data]
- Managed Blockchain
- ElastiCache [Adds a caching layer to the database for fast retrieval]
- DynamoDB Accelerator [An in-memory cache for DynamoDB]
