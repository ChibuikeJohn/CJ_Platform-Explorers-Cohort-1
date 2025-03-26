## CREATE AZURE VIRTUAL DESKTOP FOR 50 EMPLOYEE AT CONTOSO

### What Is Azure Virtual Desktop?
Azure Virtual Desktop (AVD), formerly known as Windows Virtual Desktop, is a cloud-based desktop and application virtualization service that allows users to access their virtual desktops and applications from anywhere, on any device. Key benefits include enhanced security, flexible remote work, and cost optimization.

![Intro to AVD](https://github.com/user-attachments/assets/e2826460-c50e-4247-807d-265053b98513)

### Purpose Of This Use Case For Contoso Employee
This is to allow Remote Work Solutions for all Contoso employee. This will allow them to acces the AVD wherever they are and also allow access to their work tool remotely/

## Steps To Take:
# 1. Create Azure Resource Group for Contoso
Azure Resource Group (RG), is like bucket or container for all resources within the Azure environment. I named it Chibuike RG 

a. Type Resource Group on the search button or select Resource Group from the list of services and press enter 

![Azure Resource Group Creation  _ 1](https://github.com/user-attachments/assets/0b5638fe-3520-4add-9efe-bcaf2c72c95d)

b. Select Create Button from the Menu or the Icon within the page and click Next

![Azure Resource Group Creation  _ 2](https://github.com/user-attachments/assets/bd6dae10-3cc0-4742-8ebb-c3c398ff4e32)


c.  Under Basic Tab, Select your Subscription type ( here I chossed the default subscription), Enter the desired name for the RG _ Chibuike_RG, then select the desired region ( here I choosed Europe / West Europe / or East US 2 - because it is cost effective). Click Next to proceed

![Azure Resource Group Creation  _ 3](https://github.com/user-attachments/assets/d52b9400-18e6-4525-bcc3-4c524ccebc91)

d. Under Tag Menu, you can decide to tag if you like. Put your name and the Resource Group name and click Next 

![Azure Resource Group Creation  _ 4](https://github.com/user-attachments/assets/0af77641-d665-47cb-b7a1-e163c9e424eb)

e. Under Review and Create Tab, Kindly review all the inputed values or details and click Create button

![Azure Resource Group Creation  _ 5](https://github.com/user-attachments/assets/13b121fd-2481-4e81-ba75-b50dab2d9a4f)

f. Here you have succesfully created your Resource Group... 

![Azure Resource Group Creation  _ 6](https://github.com/user-attachments/assets/3e28bdc3-3f69-4ef4-909e-69ff199dea5b)


# 2. Create Azure Virtual Network for Contoso
Azure Virtual Network a service that provides the fundamental building block for your private network in Azure. An instance of the service (a virtual network)  that enables many types of Azure resources to securely communicate with each other, the internet, and on-premises networks.

## Steps To Create Azure Virtual Network

a.  Go to all Services on Azure Portal, the select Virtual Network 

![AZ Virtual Network _ 1](https://github.com/user-attachments/assets/15f9be21-51d6-417e-9c6f-4729c46dc476)


b.  Click the CREATE tab and Click Next 

![AZ Virtual Network _ 2](https://github.com/user-attachments/assets/2c58bb86-b78f-4ef8-aebb-171f256b4eeb)


c.   Under the Basic Tab, Confirm your Recource Group e.g Chibuike_RG, type the desired Virtual Network name and select the region..
NB: Remember to use the same region all through your deployment. eg. West Europe or East US 2. Then click Next

![AZ Virtual Network _ 3](https://github.com/user-attachments/assets/0b28252b-f308-4677-9443-7969238b2b50)


d.   Under Security Tab, you can leave it as default and click Next 

![AZ Virtual Network _ 4](https://github.com/user-attachments/assets/15a673fb-2c4c-44a7-adf8-6a92677d62ec)


e.   Under IP Address, you can also leave as default and click Next.

![AZ Virtual Network _ 5](https://github.com/user-attachments/assets/a4cf268f-eefb-4176-b774-3aa169f527c5)


f.   Under Tag, you input your name to tag yourself or also leave as default , then Click Next ...

![AZ Virtual Network _ 6](https://github.com/user-attachments/assets/a40fc928-c57c-4a20-bba1-55c6436a1a55)


g.   Click on Review & Create Tab to see all the selected entries, then click CREATE button 

![AZ Virtual Network _ 7](https://github.com/user-attachments/assets/a8a8c43e-f1d0-46e8-b09e-523b9d5fb467)


h.   The deployment of Azure Virtual Network starts. Allow it to complete. Then Virtual Network is created or Completed.

![AZ Virtual Network _ 8](https://github.com/user-attachments/assets/a3eecbee-244c-42c3-bc69-2b12b40b169d)


# Step 3 - Create Azure Virtual Desktop

For us to achieve this, we need to do these 3 things
* Create Host Pool
* Create Application Group
* Create Workspace

Note: When you are creating your Host Pool, you can select either "Remote Desktop" or "Remote App."
Remote Desktop This is the full desktop within Azure, where you can log on and do your work on the full Remote Desktop
Remote App: This gives you access to only appliction on the Azure, which can be pushed to the individual computer. You only have access to this app on Azure and not the full desktop. 

Also, Host Pool Type, can be Pooled or Personal 
Personal: This is for one person having full access to the resources 
Pooled: This allows many users to share and access the full resources 










































