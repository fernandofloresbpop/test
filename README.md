# CloudFormation Template: EC2SecurityGroup
## Description
This CloudFormation template defines a set of managed policies for read-only access to various AWS services. The policies are designed to provide granular permissions for billing, containers, and security-related actions.

## Usage
Follow these instructions to use this template:

1. Deploy the stack using the AWS Management Console, CLI, or SDK.
2. Customize any parameters or settings as needed.
3. Monitor the stack’s resources and outputs.
## Prerequisites
Before using this template, ensure you have:
- An AWS account
- Permissions to create resources defined in the template
- Any specific configuration (e.g., VPC, IAM roles)
## Parameters
The template uses the following parameters:

- VpcId: The VPC ID where the security group will be created.
- SecurityGroupName: Name of the security group to be created.
## Resources
The template creates the following key resources:

- PopularReadOnlyBilling: A managed policy allowing read-only access to billing-related actions.
- PopularReadOnlyContainers: A managed policy allowing read-only access to container-related actions.

## Example Usage
Here’s an example of how to deploy this template with sample parameter values:

- Deploy the stack using the AWS Management Console.
- Specify the VPC ID and desired security group name.
- Verify that the security group is correctly configured.
