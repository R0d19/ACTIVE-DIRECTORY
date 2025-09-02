 ![Image Alt](https://github.com/R0d19/ACTIVE-DIRECTORY/blob/0991c765ddbd200d8f4fcd5596fd9a05318e6f1c/win%20server.jpg)

# ACTIVE-DIRECTORY

This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.

1 Create the Domain Controller VM (Windows Server 2022) Give your Virtual machine a name (ex: windows-server-2022)

![Image Alt](https://github.com/R0d19/ACTIVE-DIRECTORY/blob/dca8edcf97865fa7b2ae0c3f886689dd58ca0a9a/1%20.jpg)

2 Create a Resource Group,and give your resource group a name

3 Choose region 

4 Choose Image (Software that will run the Virtual Machine) (Windows Server 2022)

5 Create Username and Password for your virtual machine

6  RDP (3389) will be automatically selected

7 Click review and create

8 click next and then create

9 Review and Create to complete the Deployment

10 After Deployment, Go to Resources in Azure

11 Log into the VM using credentials created previously

12 Install Active Directory Domain Services

13 Setup a new forest as mydomain.com 

14 Create a Domain Admin user within the domain

