# Creating a SOC Network in MS Azure open to Live Traffic
![image](https://github.com/user-attachments/assets/6990dc73-690b-449e-aafc-f93847ab41bf)

## In the initial phase of this project, I built a cloud based network in Microsoft Azure consisting of a Windows 10 VM and an Ubuntu Linux VM.  I used an Azure Network Security Group to manage network traffic to both VMs activating access control lists to secure the network.  I ingested log sources from various resources within the network into a Log Analytics workspace, which was then used by Microsoft Sentinel to build attack maps, trigger alerts, and create incidents. I opened both VMs to Internet traffic and using Remote Desktop Protocol measured various security metrics within the network to ensure the environment was functioning properly and clear of potential threats.  

![image](https://github.com/user-attachments/assets/7a11e445-9980-433e-ba3e-8c202742fe65)

## Network Archiecture Configuration Breakdown 
![image](https://github.com/user-attachments/assets/b33b0b49-bd36-4172-b57d-db13e2a3f098)

## The architecture of the mini SOC Network consists of the following components:

- Virtual Network (VNet)
- Network Security Group (NSG)
- Virtual Machines (1 windows, 1 linux)
- Log Analytics Workspace
- Azure Key Vault
- Azure Storage Account
- Microsoft Sentinel



## In the Next phase of the project, I will open the Network to potentially malicious traffic by opening all Ports of the NSGs to the Internet.
# https://github.com/cyberbluz/Open_Ports
--------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------
