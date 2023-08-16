<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
Through this lab, I gained hands-on experience with setting up Active Directory, creating user accounts, managing passwords, unlocking locked accounts, and successfully logging into accounts I created.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Enabled ICMPv4 in the Windows Defender Firewall and was able to ping my domain controller through my other Virtual Machine
  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/6752f314-6407-47ce-9b74-ae8187faa58b)
![image](https://github.com/terranceharris1/configure-ad/assets/142275089/e18178b6-ff0b-408c-9577-85edb326d67e)
- Used server manager to download Active Directory on my domain controller (virtual machine)
  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/60b31600-0328-4781-afe9-73e33108ef0d)
- Promoted domain controller to server in order to create my own domain.
  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/75e7bb48-3195-4318-90c2-7127da2b1e2d)
![image](https://github.com/terranceharris1/configure-ad/assets/142275089/ab73b583-feaa-46ed-a673-a522a9e0c9c7)
- Used Active Directory to create Organizational Units and created a user for myself within the admins folder.
  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/99ae8715-2e4b-42fc-9079-fd31893e021b)
![image](https://github.com/terranceharris1/configure-ad/assets/142275089/32c399de-8db0-4735-87a7-b7f53ed92f6a)
- Promoted my account from domain user to a domain admin.
  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/2b24379b-533d-4947-846d-89800dab5742)

- Allowed Domain Users access to the domain

 ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/7e10c381-0324-4a32-8076-6810886eb34a)

- Created random users to login to the domain and placed them into the folder I created. I also was able to login,unlock the accounts I created, and reset/change the passwords. 

  ![image](https://github.com/terranceharris1/configure-ad/assets/142275089/c5fc7ab3-9a0d-4940-90d5-596d75399c0f)
![image](https://github.com/terranceharris1/configure-ad/assets/142275089/de97c301-59ef-462f-8a52-e2a431f5b6e4)


