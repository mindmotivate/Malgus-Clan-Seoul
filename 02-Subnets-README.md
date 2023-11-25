# AWS Subnet Terraform Module Overview

This Terraform configuration defines AWS subnets for both public and private access in the Tokyo region within the VPC named "app1." 

*Public Subnets:*
- `public-ap-northeast-2a`, `public-ap-northeast-2b`, and `public-ap-northeast-2c` are configured with CIDR blocks "10.88.1.0/24," "10.88.2.0/24," and "10.88.3.0/24" respectively. They are associated with availability zones "ap-northeast-2a," "ap-northeast-2b," and "ap-northeast-2c" and have the option to map a public IP on launch.

*Private Subnets:*
- `private-ap-northeast-2a`, `private-ap-northeast-2b`, and `private-ap-northeast-2c` are configured with CIDR blocks "10.88.11.0/24," "10.88.12.0/24," and "10.88.13.0/24" respectively. They are associated with availability zones "ap-northeast-2a," "ap-northeast-2b," and "ap-northeast-2c."

All subnets are tagged with metadata, including the subnet name, associated service, owner, and the relevant planet.
