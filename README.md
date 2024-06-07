
# Creation of Cluster using CloudFormation
This repository contains AWS CloudFormation templates for creating and managing clusters. 
The templates can be used to provision clusters in AWS.
# Architecture :

## Table of Contents :

1. Description
2. Prerequisites                                       
3. Installation                                                  
4. Usage                                   
5. Templates                          
6. Parameters                             
7. Outputs                             
8. Contributing                         
9. License            


  


* Description:

  
This project provides a set of AWS CloudFormation templates to create and manage clusters on AWS. The templates are designed to be reusable and customizable, allowing you to create clusters with different configurations.

* Prerequisites

  
1. An AWS account.
2. AWS CLI installed and configured on your local machine.
3. Basic understanding of AWS CloudFormation ,the AWS services involved in the cluster creation etc.
4. AWS CLI installed and configured on your local machine.



* Installation

Git clone https://github.com/yourusername/creation-of-cluster-using-cloudformation.git
cd creation-of-cluster-using-cloudformation


* Usage


1. Access resources via CloudFormation outputs.
2. Can customize parameters in the template.
3. Deploy stack.
4. Monitor creation.



* Templates

Template.yaml - Custom cluster


* Parameters


 
VpcId                 -             VPC ID	                                                                              
SubnetIds             -             Comma-separated list of subnet IDs.                                                                                  
ClusterName           - 	          Cluster name	                                                                
InstanceType	        -             EC2 instance                                                            
KeyName	              -             SSH key pairname	                                                             


* Outputs                                                                                                     


ClusterId	                                                                                                      
ClusterEndpoint	                                                                                                    
PublicID of Master Node                                                                      
PrivateID of Worker Node                                                                                 


* Contribution

Fork the repo.                                                       
Create a branch.                                                                               
Commit changes.                                                                                    
Push to branch.                                                                                  
Open a Pull Request.                                                              


* License

Licensed under the MIT License. See LICENSE for details.




































