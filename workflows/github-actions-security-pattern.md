# GitHub Actions Security Pattern

## Typical controls

- Pull request validation
- SAST before merge
- Secrets scanning
- Terraform or IaC scanning
- Container scanning before publish
- Policy checks before deployment

## Review points

- Are build secrets protected
- Are tokens scoped minimally
- Are security checks blocking or informational
- Are artifacts signed or verified where required
