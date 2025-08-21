 ![Image Alt](https://github.com/R0d19/ACTIVE-DIRECTORY/blob/0991c765ddbd200d8f4fcd5596fd9a05318e6f1c/win%20server.jpg)

# ACTIVE-DIRECTORY

This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.

Create a Resource Group,and give your resource group a name

Create the Domain Controller VM (Windows Server 2022) Give your Virtual machine a name (ex: windows-server-2022)

Choose region

Choose Availability Options (Zones)

Choose Image (Software that will run the Virtual Machine)

To Save cost, select/click Run with Azure Spot discount

Create Username and Password for your virtual machine

To access internet, select Public inbound ports, for testing choose to allow selected ports, for real live, choose none and create your own as a professional

Selectports, choose HTTP for windows and SSH for Linux, RDP will be automatically selected

Click to confirm the Licensing

click next

Review and Create to complete the Deployment

After Deployment, Go to Resources in Azure

Log into the VM and install Active Directory Domain Services

Setup a new forest as mydomain.com 

Create a Domain Admin user within the domain

