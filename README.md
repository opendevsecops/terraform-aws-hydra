[![Follow on Twitter](https://img.shields.io/twitter/follow/opendevsecops.svg?logo=twitter)](https://twitter.com/opendevsecops)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/81bbd7e4f45a46219a33696440156f93)](https://www.codacy.com/app/OpenDevSecOps/terraform-aws-hydra?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=opendevsecops/terraform-aws-hydra&amp;utm_campaign=Badge_Grade)

# AWS Hydra Terraform Module

Terraform module which deploys a scaleable security automation platform for security testnig and research.

> WARNING: work in progress

## Why Hydra

Hydra helps organisations doing better at security by providing them with the same tools attackers are using and doing it in a fully automation fashion.

## Solution Principles

The solution is heavily inspired by various AWS technologies such as AWS SQS, SNS, S3, Lambda, and ECS. With the help of these technologies Hydra can perform large scale OISINT and target fingerprinting attacks at minimal costs. Additionally, Hydra provides features which help you identify differences and locate problems which may require fixing.

## Getting Started

Getting started is easy. Here is a complete example:

```terraform
module "hydra" {
  source = "opendevsecops/hydra/aws"
}
```

This module is automatically published to the Terraform Module Registry. More information about the available inputs, outputs, dependencies, and instructions on how to use the module can be found at the official page [here](https://registry.terraform.io/modules/opendevsecops/hydra).
