# Secure CI/CD Stages

## Typical pipeline flow

Developer commit

Source repository

CI pipeline

- SAST scan
- Secrets scan
- Dependency scan
- IaC scan

Container build

Container image scan

Policy validation

Deployment approval

Secure deployment

## Goals

- Catch issues earlier in the lifecycle
- Reduce deployment of risky artifacts
- Enforce consistent delivery standards
- Improve traceability and auditability
