# Terraform-AWS-Web_app_s3 :
- This module creates a s3 bukcet for logging elb.
## Inputs :
- Bucket_name : your backet name.
- elb_service_account_arn : arn of elb service account ( needed for logs creation policy)
## Outputs :
- Web_bucket : name of web backet created.
- Instance_profile : profile of role created to allow putting logs to the backet.
