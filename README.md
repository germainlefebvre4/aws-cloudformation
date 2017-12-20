# aws-cloudformation
Templates of AWS Architectures

## Units
* VPC-NATGateway-PrivateSubnet.yml
* aws-autoscaling-AutoScalingGroup.yml.yml
* aws-autoscaling-LaunchConfiguration.yml
* aws-autoscaling-LaunchConfiguration_with-AutoScalingGroup.yml
* aws-ec2-EIP.yml
* aws-ec2-InternetGateway.yml
* aws-ec2-NatGateway.yml
* aws-ec2-Route.yml
* aws-ec2-RouteTable.yml
* aws-ec2-RouteTableAssociation.yml
* aws-ec2-SecurityGroup.yml
* aws-ec2-Subnet.yml
* aws-ec2-VPC.yml
* aws-ec2-VPCGatewayAttachment.yml
* aws-elasticloadbalancing-LoadBalancer.yml
* aws-iam-InstanceProfile.yml
* aws-iam-Role.yml
* aws-Outputs.yml
* aws-Parameters.yml


## Examples
### VPC with 1 AZ, 2 Subnet (Public and Private) and 2 Autoscaling on Bastion and WebServers
aws_1-az_2-subnets_1-bastion-asg_1-webserver-asg.yml

![alt text](schemas/AWS%20Archi%20-%201%20AZ%20V2.png)

Contents :
* 1 VPC
* 1 Avaibility Zone
* 2 subnets
  * 1 Public subnet
  * 1 Private subnet
* 1 Internet Gateway
* 1 NAT Gateway

CloudFormation contents :
* Parameters
* Resources
* Outputs

#### VPC with 1 AZ, 4 Subnets (Public and Private) and 2 Autoscaling on Bastion and WebServers
aws_2-az_4-subnets_1-bastion-asg_1-webserver-asg.yml

![alt text](schemas/AWS%20Archi%20-%202%20AZ%20V2.png)

Contents :
* 1 VPC
* 2 Avaibility Zone
* 4 Subnets
  * 2 Public subnets
  * 2 Private subnets
* 1 Internet Gateway
* 2 NAT Gateway

CloudFormation contents :
* Parameters
* Resources
* Outputs
