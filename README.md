terraform-module-s3
====

## Module that creates s3 buckets

Variables |  Required | Default Value |
---|---|---
bucket_name | yes | - |
bucket_acl | yes | - |
region  | yes | - | 

### bucket_name
The name that you want to give to the bucket

### bucket_acl
The [canned](https://docs.aws.amazon.com/AmazonS3/latest/dev/acl-overview.html#canned-acl) ACL to apply  

### region
Used to define the AWS provider region


## Variables needed from other modules

Variables  | Module |
---|---|
vpc_id | terraform-mod-vpc |
