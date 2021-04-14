# VARIABLES #

section is created to store variable information which will specified by user
i have passed the information which is account specific in the verible section

# PROVIDERS#
This is API which will connect to desire cloud providers 
here for aws cloud - i have used aws_access_key & aws_secret_key
region - value provided in the veriable section

#DATA#
This section provide information about the instance which needs to be created with specification
i have provided the aws_ami, ebs_vol, virtualization type

#RESOURCES#
This section included information about the VPC, types of subnets like private or public subnet, igw

# ROUTING #
This section include the information about the route allowed in the network using aws_route_table_association"
where IGE is attached that subnet is public subnet

# SECURITY GROUPS #
SG is important section from security point of view
SG provides the information about the inbount and outbound rules which allowed to the instances
the rules are define for inbound and outbound in this section

# LOAD BALANCER #
The Load BALANCER is created by using terraform.

# the additional scripts are written to install nginx1 and nginx2.

The overall assignment is provide you more brief network requirement which you provided

I am attaching two files which i have created for the same assignment 