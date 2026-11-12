===============================================
 ###   EC2 Instance Creation
===============================================

### Resources
* EC2 Instance -> asw_instance.main

### Inputs
* instance_type (Opotional) - # By default it will take t3.micro
* sg_ids (Mandatory) - A list of security group IDs to attch to the instance
* project (Mandatory) - Name you can give to the project
* environment (Mandatory) - In whcich environment this instance to be created
* component (Mandatory) - Which component this resource is getting created for 
* ec2_tags (Optional) - A map of tags to  attach to the instance 

### Outputs
* public_ip - Public Ip of the Instance created
* private_ip - Private Ip of the Instance created
* instance_id - INSTANCE ID of the Instance created



