This repository contains a python file which is used to clean (delete) the resources that cost money.
The python code utilizes boto3 module functions to serve its purpose.

As an example, the code in this repository considers following AWS services for the cleanup:
1. Auto Scaling Groups (ASG)
2. Load Balancers
3. NAT Gateways
4. EC2 Instances
5. EBS Volumes

However, the scope of services could be scaled based on the business requirements.
