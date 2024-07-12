# Configure Virtual Machine Lab

## Objective

The objective of this lab was to deploy and configure a Windows Server 2019 Datacenter virtual machine in Microsoft Azure, transforming it into a secure web server. This included deploying Azure Bastion for secure access, configuring virtual machine networking, resizing the virtual machine for performance improvement, and implementing Azure Disk Encryption using Azure Key Vault. This hands-on experience was designed to deepen understanding of virtual machine deployment, configuration, and management in the Azure cloud environment.

### Skills Learned

- Deploying a Windows Server 2019 Datacenter virtual machine in the Azure portal.
- Configuring a connection to a virtual machine using Azure Bastion.
- Using PowerShell to configure a custom web server through Azure Bastion.
- Configuring the DNS name and setting the DNS servers used by a virtual machine.
- Applying Azure Disk Encryption to a virtual machine's OS and data disks.
- Applying Azure Disk Encryption to the virtual machine disks.

### Tools Used

- Microsoft Azure Portal
- Azure Bastion
- PowerShell
- Azure Key Vault
- Azure Disk Encryption

## Steps
### 1. Create a Windows Virtual Machine in the Azure Portal.  
      *Ref 1: Deployed a Windows Server 2019 Datacenter virtual machine*


  ![Create Virtual Machine Basics - WM](https://github.com/user-attachments/assets/4363f11c-ceed-42d6-895a-2880d09912ee)




### 2. Configure Virtual Machine Access with Azure Bastion.
      *Ref 2: Created a subnet for Azure Bastion*
![Creating Virtual Network - VM](https://github.com/user-attachments/assets/ed031f6c-204a-4d47-b822-8f565643481d)






      *Ref 4: Configured a custom web server using PowerShell on the VM via Azure Bastion*
![Virtual Machine Name Displayed on Internet Explorer and Configured Custom Web Server - VM](https://github.com/user-attachments/assets/48ee9ec5-a4ca-4484-ba5d-3d9ed9e95660)


### 3. Configure Virtual Machine Networking.
       *Ref 5: Configured custom DNS servers for the VM*
![DNS Configuration - VM](https://github.com/user-attachments/assets/5c14cc4e-8c03-4a0c-9367-e727d23a6040)



       *Ref 6: Configured network security group rules to allow traffic on port 80*
![Adding inbound security rule allowing traffic inbound over port 80 - VM](https://github.com/user-attachments/assets/b2503031-6969-4da7-8941-86897d8873e5)

### 4. Resize a VM in the Portal.
       *Ref 7: Added an additional data disk to the VM*
![Create and Attach New Disk to VM to optimize performance - VM](https://github.com/user-attachments/assets/eadd500b-8d6f-4697-8d9e-073a6d99c3ea)



       Ref 8: Disc Volume shown in Server Manager*
![Disc Volume - VM](https://github.com/user-attachments/assets/75e1ffd2-b95c-4518-ad66-843fed9279b3)

### 5. Encrypt a Windows VM with Azure Encryption.
       *Ref 8: Set up Azure Key Vault*
![Creating Key Vault and Enabling Azure Disc Encryption - VM](https://github.com/user-attachments/assets/7b217584-c263-470e-be7e-13952531a23a)



        *Ref 8: Applied Azure Disk Encryption to the VM's OS and data disks*
![Disc Encryption is Enabled - VM](https://github.com/user-attachments/assets/147e8603-ca58-47e5-a1c9-059de5267565)


### 5. Lab Completed.




