# Ansible_AWS
A branch for EC2 deployment with different parameters

EC2 & Security group - is a .yml playbook with the script, which creates an SG with pr-defined open ports and CIDR and deploys an EC2 instance with non-default volume.
Ansible_Subnet - is a .yml playbook with the script, which creates a Subnet with defined CIDR and attached to existnig VPC.
volumes.yml - playbook to create independent volume (not attached to any EC2) with variable, for further use.
