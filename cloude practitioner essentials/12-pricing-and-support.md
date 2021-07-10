# Free Tier

The free tier has three categories:

1. Always free
2. 12 months free
3. Trials

# Pricing Concepts

1. Pay for what you use
2. Pay less when you reserve: **Commit to 1 or 3 year contract for a specific usage and get a lower $/hour price**
3. Volume based discounts

# AWS Lambda

Lambda is charged for the number of invocations and the time it takes to run the functions.

Part of the `Always Free` tier, Lambda gets `1 million` free requests per month and `3.2 million seconds` compute time per month.

# EC2

> Free tier for 12 months: 750 hrs active use of t3.micro instances

EC2 instances are charged by the amount of active compute time per month, the amount of EBS storage used and the length of time Elastic Load Balancing has been used.

# S3

> Free tier for 12 months: 5gb storage, 20,000 GET, 2,000 PUT/POST and 15gb data transfer per month

Ongoing cost factors:

1. Number of monthly requests to add or retrieve objects from the bucket
2. Amount of storage used

# Billing

The Cost Management Console includes tools to:

- Compare your current month-to-date balance with the previous month, and get a forecast of the next month based on - current usage.
- View month-to-date spend by service.
- View Free Tier usage by service.
- Access Cost Explorer and create budgets.
- Purchase and manage Savings Plans.
- Publish AWS Cost and Usage Reports.

# Consolidating Bills

The firm gets a consolidated bil for all the accounts within the organization which is itemized for unit cost and usage of resources.

# AWS Budgets

Set a cost budget and an alert for when a target % is hit:

![Screenshot from 2021-07-05 07-05-42](https://user-images.githubusercontent.com/73107656/124424725-70db8b80-dd5f-11eb-91f3-d0149730ae9a.png)

# AWS Cost Explorer

![Screenshot from 2021-07-05 07-11-18](https://user-images.githubusercontent.com/73107656/124425257-37efe680-dd60-11eb-8156-55e769c50c6f.png)

# Support Plans

Four levels:

1. Basic
2. Developer
   - Best practice guidance
   - Client-side diagnostic tools
3. Business
   - Use-case guidance to identify AWS offerings, features, and services that can best support your specific needs
   - All AWS Trusted Advisor checks
4. Enterprise
   - Application architecture guidance, which is a consultative relationship to support your company’s specific use cases and applications
   - Infrastructure event management: A short-term engagement with AWS Support that helps your company gain a better understanding of your use cases.
   - This also provides your company with architectural and scaling guidance.
   - A `Technical Account Manager`

**TAM**: Technical Account Managers are direct contacts able to advise on the five pillars with a focus on supporting success.

# AWS Market Place

![Screenshot from 2021-07-06 06-39-25](https://user-images.githubusercontent.com/73107656/124547973-ee1d0400-de24-11eb-9022-1255695d50cf.png)

---

# Always Free

**DynamoDB**: 200 million requests per month, 25 write cap units, 25 read cap units, 25 gb storage

**S3 Glacier**: 10 gb storage - using the Glacier api

**AWS Lambda**: 1 million requests per month and up to 3.2 million seconds of compute time per month

# 12 Months Free

**EC2**: 750 hrs of linux t3.micro

**S3**: 5 gb, 20,000 GET, 2,000 PUT

**RDS**: 750 hrs

**CloudFront**: 50gb transfer out, 2,000,000 http/https requests per month

# Estimating EC2 costs

- Clock hours of server time
- Instance type
- Pricing model
- Number of instances
- Load balancing
- Detailed monitoring
- EC2 auto scaling
- Elastic IP addresses
- Licensing

# Lambda

- Request pricing:

  - **Free tier**:1 million p/m, 400,000 gb-seconds compute time
  - $0.20 per million requests thereafter

- Duration pricing:
  - **Free tier**: 400,000 GB-seconds per month free, up to 3.2 million seconds of compute time
  - $0.00001667 for every GB-second used thereafter

# EBS - Elastic Block Store

- SSD: optimized for IOPS

- HDD: optimized for throughput

Pricing factors:

1. Volumes
2. Snapshots
3. Data Transfer (outbound)

# S3

Pricing factors:

1. Storage class
2. Storage volume
3. Requests and Data retrievals
4. Data transfer out
5. Management features
