# Terraform-AWS-Web_app_s3 :
- This module creates a s3 bukcet for logging elb.
## Inputs :
- Bucket_name : your backet name.(string)
- elb_service_account_arn : arn of elb service account ( needed for logs creation policy) (string)
## Outputs :
- Web_bucket : name of web backet created. (string)
- Instance_profile : profile of role created to allow putting logs to the backet.(object)
