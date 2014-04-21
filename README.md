#cloudformation
==============

##CloudFormation Scripts

###DrupalStack
AWS CloudFormation Template multi-tier web-app-in-vpc.template: 
1. Creates a VPC public subnet  with: 
    a. ELB
    b. NAT
    c. Bastion host  
2. Private WebServer subnet for EC2 Drupal instances 
3. Multi-az Amazon RDS database instance for storage 

**WARNING** This template creates one or more Amazon EC2 instances, an Elastic Load Balancer and an Amazon RDS database. You will be billed for the AWS resources used if you create a stack from this template.


