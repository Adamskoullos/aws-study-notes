# Local Storage

**Amazon Elastic Block Storage** (**EBS**) provides persistent data storage even after the EC2 instance is terminated.

An EBS **snapshot** is an incremental backup of the data within EBS and only updates the changes.

# Amazon Simple Storage S3

Stores data `objects` within `buckets`:

1. **S3 Standard**: Good for frequent access (static website)
2. **S3 Standard-IA**: Lower storage cost, higher retrieval cost
3. **S3 One Zone-IA**: Stores data in a single AZ and costs less than `Standard-IA`
4. **S3 Intelligent-Tiering**: Can automate data store tier as the data reaches specific time horizons
5. **S3 Glacier**: Low cost long term storage. retrieve in minutes or hours
6. **S3 Glacier Deep Archive**: Lowest cost long term storage for archiving. 12 hour retrieval notice period.

# Amazon Elastic File System (EFS)

Where EBS storage is accessible only to EC2 instances within the same AZ, EFS is Regional meaning any AZ within the Region has access to the storage. Also unlike EBS, EFS scales automatically and demand increases.

# Amazon RDS

RDS is a managed service that takes care of hardware and set-up, patching and backups.

RDS provides security options for encryption in storage and transit and is available on six database engines:

1. Amazon Aurora
2. PostgreSQL
3. MySQL
4. MariaDB
5. Oracle Database
6. Microsoft SQL Server

> **Aurora** is up to 5x faster than MySQL and 3x faster than PostgreSQL

# Amazon DynamoDB

> DymanoDB is a **serverless** NoSQL database that stores `Key: Value` pairs in **tables**

- A one millisecond response time
- Automatic scaling

**DAX** is the Amazon DynamoDB Accelerator and is an in memory cachetaking response times down from milliseconds to microseconds.

# DocumentDB

DocumentDB is also a NoSQL database and supports MongoDB workloads. This is a managed service and automatically scales. Can be used with massive read and write volumes and works with JSON.

# Redshift

Redshift is the data wharehouse to store and directly access huge amounts of historical data for big data analysis.

# AWS Database Migration Service (DMS)

Database migration can be to the same or different database type and can be used for taking a firms databse into the cloud frm on-premises, database consolidations and continuous database replication.

# Amazon Neptune

A graph database that is designed to efficiently query highly connected datasets and is a fully managed service.

# Amazon Quantum Ledger Database (QLDB)

QLDB is a centrally managed immutable database that logs details for every transaction/event/change.

# Amazon Managed Blockchain

Create and manage blockchain networks without a central authority

# Amazon ElastiCache

A caching layer that can be added to a database to improve read times for common requests.

Supports Redis and Memcached
