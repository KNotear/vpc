<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | 5.49.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.49.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_internet_gateway.tf_igw](https://registry.terraform.io/providers/hashicorp/aws/5.49.0/docs/resources/internet_gateway) | resource |
| [aws_vpc.tf_vpc](https://registry.terraform.io/providers/hashicorp/aws/5.49.0/docs/resources/vpc) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_pjt_name"></a> [pjt\_name](#input\_pjt\_name) | 변수 블록 | `string` | `"module-test"` | no |
| <a name="input_vpc_cidr_block"></a> [vpc\_cidr\_block](#input\_vpc\_cidr\_block) | n/a | `string` | `"172.16.0.0/16"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_igw_id"></a> [igw\_id](#output\_igw\_id) | n/a |
| <a name="output_vpc_id"></a> [vpc\_id](#output\_vpc\_id) | 아웃풋 블록 |
<!-- END_TF_DOCS -->
