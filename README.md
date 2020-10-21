terraform-module-s3
====

# Module that creates s3 buckets

This module creates single bucket.


It will create:
- s3 bucket


## Inputs
Variables |  Optional | Default Value | Example | Description
---|---|---|---|---|
bucket_name | yes | - | mybucket | The name that you want to give to the bucket
bucket_acl | yes | - | private | The [canned](https://docs.aws.amazon.com/AmazonS3/latest/dev/acl-overview.html#canned-acl) ACL to apply  
region  | yes | - | us-east-1 | Used to define the AWS provider region

## Outputs

None

## Dependencies

Variables  | Module | Description
---|---|---|
vpc_id | terraform-mod-infra | -
