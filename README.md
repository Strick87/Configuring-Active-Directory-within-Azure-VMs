<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Provision Azure Virtual Machines for AD Deployment.
- Step 2 Configure Networking Between Virtual Machines.
- Step 3 Install and Configure Active Directory Domain Services.
- Step 4 Verify Domain Join and Test Connectivity.


<h2>Deployment and Configuration Steps</h2>


![image](https://github.com/user-attachments/assets/b1e911a5-6481-439a-b80a-fed3c24957c8)

<p>

</p>
<p>
Step 1-This screenshot shows the configuration of a virtual machine in Azure. The VM is set up with Windows 10 Pro (version 22H2), 2 vCPUs, and 8GB of memory. The administrator account has been configured, and the estimated monthly cost is displayed. This VM will serve as the base for deploying on-premises Active Directory in the cloud.






![image](https://github.com/user-attachments/assets/02f1c5e9-8e8f-4ae2-900d-ac0fbf8fe7ee)





Step 2-This screenshot captures the Server Manager dashboard on Windows Server 2022. Here, I began configuring the local server by selecting "Add roles and features," a critical step in preparing the system for Active Directory Domain Services installation.













![image](https://github.com/user-attachments/assets/9873987f-a8c2-4341-97ea-39a94ca28de7)



<p>

</p>
<p>
Step 3-This diagram illustrates the process of joining a Windows 10 virtual machine (Client-1) to a domain managed by the domain controller (DC-1) within an Azure Virtual Network. It highlights the DNS configuration and the communication flow required for domain integration in a hybrid cloud setup."








![image](https://github.com/user-attachments/assets/9623e722-1a6b-4aa2-9370-544894cafb14)



Step 4-This PowerShell screenshot confirms the virtual machine's hostname (client-1) and its successful connection to the domain. It also displays essential network configurations, including the DNS server settings, verifying the VM's integration into the domain environment.





