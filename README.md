This is AWS terraform provisioner demo with executing app.py python file at remote instance with provisioner.

Resources Provisioned
Terraform Project -> KeyPair & VPC & Public Subnet & Routing Table (igw) & Security Group & EC2 instance 

Provisioner used file and remote-exec

To ssh to the terraform created instance -> ssh -i ~/.ssh/id_rsa ubuntu@<instance_public-ip>
