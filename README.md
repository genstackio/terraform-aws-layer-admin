# AWS Admin Terraform module

Terraform module which creates the resources to host a web admin on AWS.

## Usage

```hcl
module "admin" {
  source      = "genstackio/admin/aws"

  bucket_name = "s3"
  dns         = "admin.mydomain.com"
  dns_zone    = "id-of-the-route53-zone"
}
```
