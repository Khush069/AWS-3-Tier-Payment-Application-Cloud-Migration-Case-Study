# AWS-3-Tier-Payment-Application-Cloud-Migration-Case-Study

End-to-end cloud migration case study for a 24x7 payment
application migrating from an on-premises VMware environment
to AWS.

This case study is based on real-world cloud migration
experience and has been sanitized and generalized for
public demonstration.

---

## Business Scenario

A payment application running on VMware infrastructure needs
to be migrated to AWS with minimal downtime while maintaining
business continuity.

## Migration Objectives

- Minimal downtime
- RTO: 30 minutes
- RPO: 5 minutes
- Multi-AZ architecture
- Improved security
- Infrastructure automation
- Operational readiness

## Existing Environment

On-premises VMware environment containing:

- Windows application servers
- Linux servers
- PostgreSQL database
- Shared storage
- Internal load balancer
- Monitoring

## Target AWS Architecture

- Amazon VPC
- Application Load Balancer
- Amazon EC2
- Amazon RDS for PostgreSQL
- AWS storage services
- IAM
- AWS Secrets Manager
- AWS KMS
- Amazon CloudWatch
- AWS CloudTrail
- VPC Flow Logs

## Migration Approach

1. Discovery
2. Assessment
3. Dependency mapping
4. AWS architecture design
5. Infrastructure foundation
6. Pilot migration
7. Application migration
8. Database migration
9. Production cutover
10. Validation
11. Operational handover

## Infrastructure as Code

Terraform modules are used to provision reusable AWS infrastructure.

## CI/CD

GitLab CI/CD is used for:

- Terraform validation
- Terraform plan
- Controlled production deployment

## Documentation

See the `docs/` directory for:

- Architecture
- Security
- Migration strategy
- Cutover
- Rollback
- Runbooks
- Operational readiness

## Important Note

This repository contains a sanitized and representative
case study based on real-world cloud migration experience.
Customer names, infrastructure details, credentials,
IP addresses, and confidential information have been removed.
