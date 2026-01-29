## PR Checklist – Infrastructure Change

Please confirm before requesting review:

- [ ] terraform fmt -recursive
- [ ] terraform validate
- [ ] terraform plan -var-file="environments/test.tfvars"

### Summary
Describe the infrastructure change:

### Risk
Low / Medium / High

### Rollback Plan
Revert PR and re-apply previous tag.
