# Azure-Virtual Machines Set up
<p align="center">

  
![image](https://github.com/user-attachments/assets/9326b07d-2fb3-4cb8-b589-0f320a73421b)
</p>

<h1> Setting up two Virtual Machines in the Cloud (Azure)</h1>
This lab outlines a hands-on project of setting up two Virtual Machines (VMs) in azure. The goal is to create a resource group in Azure containing two VMs, both within the same virtual network. One VM will be setup as a server, and the other VM will be set up as a Client machine.

<h2>Project Diagram</h2>

![image](https://github.com/user-attachments/assets/f3d594e2-f63b-48aa-8c55-101501a38509)




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High Level Deployment and Configuration Steps<:</h2>

Resource Group and Virtual Network Set Up:
 - Create a Resource Group.
 - Create A Virtual Network
   
Create Two Virtual machines:
 - Set up a Virtual machines using windows server 2022.
 - Set up a Virtual machines using windows 10.

<h2>Deployment and Configuration Steps</h2>

<p>

Set Up Azure Resources:
- Create a Resource Group to house the VMs and the virtual network.

![image](https://github.com/user-attachments/assets/1e675c3c-63ba-42d2-a60f-6bdf9d6e4193)

- Set up a Virtual Network (VNet) that the VMs will use to communicate.

 ![image](https://github.com/user-attachments/assets/71e63817-04e2-4ffc-9d01-b2bece573120)


 ![image](https://github.com/user-attachments/assets/543ae988-f33d-44ff-ab0d-771ae2b3926f)

Set up a Virtual machines using windows server 202
- Create the virtual server and select the resource group and virtual network created in the above set

![image](https://github.com/user-attachments/assets/1e9eaeaf-9abb-4504-bad8-740c9ad13879)

![image](https://github.com/user-attachments/assets/0139e556-ad9b-4e46-b506-d2691b4be34a)


![image](https://github.com/user-attachments/assets/1969e224-a305-4627-99ce-578556de0c83)



Set up a Virtual machines using windows 10.
- Create the virtual and place it in the same resource group and virtual network as the serever

![image](https://github.com/user-attachments/assets/27520bf0-5f0b-45a4-8254-09d02b80b728)

![image](https://github.com/user-attachments/assets/72db264f-ff4e-4245-9340-7bfb312dcb58)


</p>
<p>
<h2>Conclusion:</h2>
This project walks through how to create a windows server virtual machine and windows 10 virtual machine in the same resource group and virtual netwok. It demonstrates essential skills for anyone looking to get hands-on experience with creating virtual machines in Azure.
</p>
<br />
