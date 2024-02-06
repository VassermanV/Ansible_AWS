# Ansible_AWS
A branch for EC2 deployment with different parameters

- EC2 & Security group - is a .yml playbook with the script, which creates an SG with pr-defined open ports and CIDR and deploys an EC2 instance with non-default volume.
- Ansible_Subnet - is a .yml playbook with the script, which creates a Subnet with a defined CIDR and is attached to existing VPC.
- volumes.yml - playbook to create independent volume (not attached to any EC2) with variable, for further use.
- status_security_group.yml -  playbook to see detailed information regarding all existing SG in specified VPC (by adding vpc-id parameter) or detailed information, regarding specific SG, by adding group-id parameter.
- vpc_subnet_info.yьд - playbook to see detailed information regarding all existing subnets in specified VPC (by adding vpc-id parameter).
