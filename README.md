# nested-planner-web
## Project Setup
- Install and setup `aws` and `terraform` cli's beforehand
- Change the bucket name in `package.json` under `scripts.deploy` (currently set to `nested-planner`, but obviously that one's taken)
- Run `terraform init && terraform apply` with *your* chosen bucket name
- On code change, run `yarn deploy`
