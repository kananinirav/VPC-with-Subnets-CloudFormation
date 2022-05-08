# VPC-with-Subnets-CloudFormation

A virtual network in the AWS cloud
When you provision a service within a public cloud, it is effectively open to the world and can be at risk of attacks from the internet. In order to secure resources against attacks from the outside, you lock them within a VPC. VPC restricts what sort of traffic, IP addresses, and also the users that can access your resources. In other words, VPC is your network but in the cloud.

Just to be clear, AWS has already created a default VPC for you to use so that you don’t have to create and configure your own VPC. But, by default, its subnet in each AZ is a public subnet, because the main route table sends the subnet’s traffic that is destined for the internet to the internet gateway.

This will help you how to create a fully functional custom VPC from scratch with a pair of public and private subnets using AWS CloudFormation.

We are creating following resources :

1. VPC
2. Internet Gateway
3. Subnets ( Prublic and Private )
4. Route table for Subnets
5. NAT Gateway for private Subnet

For More Details : https://medium.com/@kanani-nirav/create-a-vpc-with-private-and-public-subnets-using-cloudformation-939114a38f22
