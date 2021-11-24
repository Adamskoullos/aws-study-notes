# AWS Amplify

- [Introduction]()
- [CloudFormation]()
- [CloudWatch]()
- [Pinpoint]()
- [CI/CD Pipeline]()

---

## Introduction

Amplify is a serverless backend that allows the user to utilise multiple AWS services without the need to manually set up and configure them. Static sites are served from AWS `CloudFront`, AWS's CDN.

Under the hood Amplify uses `CloudFormation` which is touched upon further down.

Here is a list of services available within Amplify:

- Authentication > **`Cognito`**
- DataStore > **`DynamoDB`**
- Managed Hosting >
- Manage Users > **`IAM`**
- API (GraphQL, REST) > **`AppSync`**
- Cloud Functions > **`Lambda`**
- CI/CD >
- Manage Content >
- Storage > **`S3`**
- Analytics > **`Pinpoint`**
- PR Preview >
- Extensibility >
- Geo >
- AI/ML Predictions >
- Monitoring > **`CloudWatch`**
- Interactions >
- Push Notifications >
- Custom Domains > **`Route 53`**
- PubSub > **`SNS`**

---

## CloudFormation

CloudFormation is an infrastructure as code service.

A complete model/snapshot of the systems infrastructure, rules, logic, everything, is copied and pasted. This allows further instances to be implemented quickly with low set up costs. This reduces the risk of human inconsistencies also reducing the risk of unforeseen costs.

Amplify can quickly create new instances.

### Key Concepts

1. The formation of a new instance is created from either a `.yaml` or `.json` file which contains all the resources used.

2. `Stacks` are logical groupings of template resources.

3. `Changesets` are a preview of the differences between the existing instance and the new instance that is being initialised/uploaded.

---

## CloudWatch

[AWS Amplify Monitoring](https://docs.aws.amazon.com/amplify/latest/userguide/access-logs.html) using CloudWatch

---

## Pinpoint

---

## CI/CD

Amplify Console can be linked up to Github repos to implement an automated pipeline.
