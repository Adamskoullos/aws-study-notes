# The five Pillars

1. IAM
2. Detection
3. Infrastructure protection
4. Data Protection
5. Incident Response

# Security Design principles

- Implement a strong identity foundation
- Fine-grained access controls
- Security at all layers
- Automate security best practices
- Prepare for security events and automation

# Securely Operate

- Group accounts with specific access controls and permissions
- Use Organizations and Control Tower tools

# IAM

> Managing human and machine identities:

- IAM
- Strong sign in mechanisms
- Centralized identity provider
- Secure secrets

> Manage permissions for human and machine identities:

- Define access requirements
- Grant least privilege
- Limit public and cross account access
- Reduce permissions continuously

> Amazon Cognito

- Supports multiple login providers
- Unique users/devices
- Implement security best practices

# Detective Controls

- Lifecycle controls to establish operational baselines
- Internal auditing to examine controls
- automated alerting

# Automating misconfiguration detection and response

**AWS Config** is used to record resource configuration, evaluate changes as they occur against the config rules and set automated responses to misconfigurations.

# Infrastructure Protection

- Trust boundaries
- Operating system
- System security configuration
- Policy enforcement points

> Control traffic at all layers:

- Use Edge services: Cloudfront, WAF
- Divide the VPC into layers using subnets
