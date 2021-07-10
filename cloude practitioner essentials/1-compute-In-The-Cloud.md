# EC2

Each EC2 instance is a virtual server and can be configured by the following factors:

1. OS (Linux or Windows)
2. The instance type: the hardware resources configuration
3. Applications to run on the server
4. Security settings

# EC2 Instance Types

1. General purpose
2. Compute optimized
3. Memory optimized
4. Accelerated computing
5. Storage optimized

# EC2 Pricing

1. **On-Demand**:
2. **Savings Plans**: EC2, Lambda, Fargate
   - savings up to 72%
   - 1 & 3 year term
3. **Reserved Instances**:
   - 1 & 3 year term
4. **Spot Instances**:
   - Up to 90% savings
   - AWS can cancel with at very short notice
5. **Dedicated Hosts**:
   When EC2 instances are hosted on their own physical servers and not multi-tenancy.

# Auto Scaling EC2

Decoupled scaling allows the provision of different hardware configurations depending on where the over capacity or bottle necks are.

Scaling can be undertaken vertically by adding more capacity to an instance to complete larger tasks or horizontally adding more instances to undertake more small tasks at the same time.

- Dynamic Scaling

- Predictive Scaling

An **Auto Scaling Group** can be set to create a `minimum` and `maximum` number of instances for auto scaling to range between. A **desired** setting can also be set.

# Elastic Load Balancing (ELB)

ELB is positioned at the `Region` level and distributes traffic evenly between EC2 instances. It scales up and down with EC2 instances and traffic volumes.

ELB also operates as the link between front-end and back-end instances allowing the back-end instances to scale as demand increases and decreases without effecting the front-end.

# AWS promotes a loosely coupled architecture through a microservices approach

Amazons **Simple Queue Service** **SQS** and **Simple Notification Service** **SNS** services are used to as the middle men between micro-services and allow provisions to manage holdups and failures by individual micro-services.

- **SNS** is a pub/sub service, subscribers can be web servers, email addresses, AWS Lambda functions etc..

- **SQS** can send, store and receive messages between software components.

# Compute service options

1. Full control of environment including OS: EC2
2. No management of servers: AWS Lambda (serverless)
3. Docker container based workloads: ECS (Amazon Elastic Container Service)
   - Serverless: AWS Fargate
   - Traditional: EC2
