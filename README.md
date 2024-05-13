# VPC Peering Using CloudFormation

This repo contains two CloudFormation Stacks that will allow you to create a VPC Peering Connection between two
VPCs in the same AWS Account and same Availability Zone.
It also deploys resources to test the connection such as Subnet in each VPC and an EC2 Instance in each Subnet,
as well as Internet Gateways and Route Tables for each VPC.

## Deploying the Stacks in CloudFormation

For step-by-step instructions as well as an overview of VPC Peering Connections, its benefits, disadvantages and use cases, 
check out my blog: (Insert blog link).
To deploy this solution, first deploy the Networking Stack; `networking.yaml`, 
followed by the EC2 Instance stack; `ec2.yaml` in the CloudFormation Console.

