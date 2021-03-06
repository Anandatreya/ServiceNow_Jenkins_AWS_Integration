# ServiceNow_Jenkins_AWS_Integration
This is an integration project between ServiceNow, Jenkins and AWS to show case the integration of three worlds - ITSM, DevOps and the Cloud.
The intention of this project is to enable a simple AWS EC2 server provisioning mechanism from a ServiceNow Technical Catalog item. 
The simplest use case for this project could be a developer who would want an EC2 server provisioned as per a standard specification.
A more advanced use case would be to provide developers a choice of multiple server types within AWS (Ubuntu OS, Microsoft, RedHat etc..) 
and /or server of different specifications (t2.micro. etc..)
A second use case of this project could be to use AWS CLI’s rich command structure to provision environments supported by AWS Cli. 
Another use case would be to configure multiple ServiceNow catalog items to allow Jenkins to connect to multiple cloud environments such as Microsoft Azure 
and Google Cloud to provision basic servers in those environments.
I have used ServiceNow as the ITSM product; this solution could be extended to allow other ITSM products such as BMC Remedy, HP Service Manager to integrate with Jenkins to allow this integration.

