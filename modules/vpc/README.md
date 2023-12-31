<!-- markdownlint-configure-file {
  "MD033": false,
  "MD041": false
} -->

<!-- BEGIN_TF_DOCS -->
<!-- Content between BEGIN_TF_DOCS and END_TF_DOCS is generated by terraform-docs. -->
<!-- Run `terraform-docs .` in the base repository directory to regenerate. -->

## Requirements

No requirements.

## Providers

| Name                                             | Version |
| ------------------------------------------------ | ------- |
| <a name="provider_aws"></a> [aws](#provider_aws) | n/a     |

## Modules

No modules.

## Resources

| Name                                                                                                                                        | Type        |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [aws_eip.natgw](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eip)                                            | resource    |
| [aws_internet_gateway.igw](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/internet_gateway)                    | resource    |
| [aws_nat_gateway.natgw](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/nat_gateway)                            | resource    |
| [aws_route_table.rt-private](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)                       | resource    |
| [aws_route_table.rt-public](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table)                        | resource    |
| [aws_route_table_association.private1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association) | resource    |
| [aws_route_table_association.private2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association) | resource    |
| [aws_route_table_association.private3](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association) | resource    |
| [aws_route_table_association.public1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)  | resource    |
| [aws_route_table_association.public2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)  | resource    |
| [aws_route_table_association.public3](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association)  | resource    |
| [aws_subnet.private1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                   | resource    |
| [aws_subnet.private2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                   | resource    |
| [aws_subnet.private3](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                   | resource    |
| [aws_subnet.public1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                    | resource    |
| [aws_subnet.public2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                    | resource    |
| [aws_subnet.public3](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet)                                    | resource    |
| [aws_vpc.main](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc)                                             | resource    |
| [aws_availability_zones.available](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/availability_zones)       | data source |

## Inputs

| Name                                                                                             | Description | Type     | Default | Required |
| ------------------------------------------------------------------------------------------------ | ----------- | -------- | ------- | :------: |
| <a name="input_cidr_block"></a> [cidr_block](#input_cidr_block)                                  | n/a         | `string` | n/a     |   yes    |
| <a name="input_private_subnet_1_cidr"></a> [private_subnet_1_cidr](#input_private_subnet_1_cidr) | n/a         | `string` | n/a     |   yes    |
| <a name="input_private_subnet_2_cidr"></a> [private_subnet_2_cidr](#input_private_subnet_2_cidr) | n/a         | `string` | n/a     |   yes    |
| <a name="input_private_subnet_3_cidr"></a> [private_subnet_3_cidr](#input_private_subnet_3_cidr) | n/a         | `string` | n/a     |   yes    |
| <a name="input_public_subnet_1_cidr"></a> [public_subnet_1_cidr](#input_public_subnet_1_cidr)    | n/a         | `string` | n/a     |   yes    |
| <a name="input_public_subnet_2_cidr"></a> [public_subnet_2_cidr](#input_public_subnet_2_cidr)    | n/a         | `string` | n/a     |   yes    |
| <a name="input_public_subnet_3_cidr"></a> [public_subnet_3_cidr](#input_public_subnet_3_cidr)    | n/a         | `string` | n/a     |   yes    |

## Outputs

| Name                                                  | Description |
| ----------------------------------------------------- | ----------- |
| <a name="output_vpc_id"></a> [vpc_id](#output_vpc_id) | n/a         |

<!-- END_TF_DOCS -->
