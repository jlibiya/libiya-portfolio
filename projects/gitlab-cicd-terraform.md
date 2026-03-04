# GitLab CI/CD + Terraform Delivery

## Summary
Created GitLab pipeline templates for Terraform plan/apply with approvals and safer environment promotion.

## What I built
- Pipeline stages: validate → plan → security checks → apply (manual)
- Remote state and workspace/environment separation
- Reusable Terraform modules
- Drift detection job (scheduled)

## Results / Impact
- Reduced provisioning failures
- Faster environment creation
- Improved auditability and repeatability

## Tech
GitLab CI/CD, Terraform, AWS/GCP, IAM, Security scanning

## Links
- Code: https://github.com/<your-username>/<repo-name>