# HB_HC_MPI
Templates and scripts for provisioning HC44rs virtual machines

The template in the master branch will create a single VM on an existing VNet with no public-IP.
Customizations have been added for specific project and set as defaults.
The OS will be CentOS 7.6 (version: 7.6.20181219)


There post install script will load all of the drivers and libraries necessary for running MPI jobs.



[![Click to deploy template on Azure](http://azuredeploy.net/deploybutton.png "Click to deploy template on Azure")](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faqualkenbush%2FHB_HC_MPI%2Fmaster%2Fazuredeploy.json)  

