# Terraform PR Checklist

Please ensure the following before merging:

- [ ] Run `terraform fmt -recursive` → all files formatted
- [ ] Run `terraform validate` → no errors
- [ ] Run `terraform plan -var-file="environments/test.tfvars"` → plan reviewed
- [ ] Verify changes are only for intended environment
- [ ] Check module outputs and variables
- [ ] Commit messages follow conventions
