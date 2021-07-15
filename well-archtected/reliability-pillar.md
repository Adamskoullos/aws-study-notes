# Main focus

- Ability to recover from infrastructure disruptions
- Dynamically acquire resources to meet demand
- Mitigate disruptions

1. Foundations
2. Workload architecture
3. Change management
4. Failure management

# Reliability design principles

- Automatically recover from failure
- Test recovery procedures
- Ability to scale horizontally to increase aggregate workload availability
- Stop guessing capacity
- Manage change in automation

# Network topology

- Sufficient bandwidth to data center

# Workload Architecture

- Service-orientated or microservices architecture
- Designed to prevent failures
- designed to mitigate failures

# Change Management

- Monitor behavior
- AWS SNS
- Review
- CloudWatch

- Create an environment that auto scales up and down with demand
- Use runbooks
- Integrate testing into the CI/CD pipeline
- Use immutable infrastructure

# Failure Management

- Automate response
- Analyse
- Back up data:
  - Define objective
  - Backup strategy
  - periodic recovery testing
  - Automated recovery
  - Periodic reviews
- Recover

# Fault isolation

- Use multiple AZ's
- Use multiple regions
- Bulkhead architecture
