<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

https://youtu.be/ikG959Q5t9E?si=jcBB2xyXYvNsdCFl

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

Create an Azure Virtual Machine Windows 10, 4 vCPU
Log into the VM with Remote Desktop


<h2>Installation Steps</h2>

Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files”
We will use the files in this folder to install osTicket and some of the dependencies.

![image](https://github.com/user-attachments/assets/6f85b608-b85e-4242-9c46-d7766b3c40a2)

![image](https://github.com/user-attachments/assets/25541ee0-0173-427a-b408-9ea9eaa45dc5)

![image](https://github.com/user-attachments/assets/1c03c673-0325-48c9-a214-7c9c61fcff81)

Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI

![image](https://github.com/user-attachments/assets/94391697-9cd5-4421-af7a-e3fa64e5ed0f)

![image](https://github.com/user-attachments/assets/02a2c551-9c86-4998-88d8-8bb00ea3d229)

![image](https://github.com/user-attachments/assets/b6ab213a-5477-4168-9db0-74d1292844a2)

![image](https://github.com/user-attachments/assets/5bf34260-0254-454b-8bc9-fda73fb12efe)

![image](https://github.com/user-attachments/assets/7f65d4be-7ff9-48c1-b141-07815d9cecb9)

From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

![image](https://github.com/user-attachments/assets/54540950-64e0-4ca8-9a1d-3181aa893cf0)

![image](https://github.com/user-attachments/assets/f3ee770e-3dec-488b-ac66-5e2ca879c848)

![image](https://github.com/user-attachments/assets/bd1b39c1-1a73-4ef8-8f12-0b5547806302)

From the “osTicket-Installation-Files” folder install the Rewrite Module (rewrite_amd64_en-US.msi)

![image](https://github.com/user-attachments/assets/10725281-0a4f-43e9-9ba0-1e27bf800321)

![image](https://github.com/user-attachments/assets/9fd70c61-b47b-4ca5-980e-71227f675208)

Create the directory C:\PHP

![image](https://github.com/user-attachments/assets/81642775-e339-40f0-ae4a-2ec7c8194c58)

From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder

![image](https://github.com/user-attachments/assets/aed27e07-d524-4c2d-9029-2cb549d30438)

![image](https://github.com/user-attachments/assets/d1b06864-a307-45d2-b7b2-f513e9096813)

![image](https://github.com/user-attachments/assets/33253f2f-2d81-4cfc-9cec-ab1acb05bda5)

![image](https://github.com/user-attachments/assets/ff7e59bd-eac6-4096-bd41-643dc3ed552d)

![image](https://github.com/user-attachments/assets/f26f1e6e-a197-4f37-b765-042ef265aaed)


From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.

![image](https://github.com/user-attachments/assets/e8e1051c-e760-40ee-9b4a-c0890a89db6d)


From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)

Typical Setup ->

Launch Configuration Wizard (after install) ->

Standard Configuration ->

Username: root

Password: root


![image](https://github.com/user-attachments/assets/778eb7cd-c1e4-41b2-96ff-cee40c34c448)

![image](https://github.com/user-attachments/assets/b12afc0d-37cb-4a43-9090-15f346c06d4c)


![image](https://github.com/user-attachments/assets/7ac16ab9-4387-4a2a-a99d-1901d21b45cd)


![image](https://github.com/user-attachments/assets/ee868745-4007-445f-aad4-48a97e423254)

![image](https://github.com/user-attachments/assets/0d303c59-503c-4690-a0af-9878627365f9)

![image](https://github.com/user-attachments/assets/cecad311-6a40-453a-af84-846e335ef2c4)

![image](https://github.com/user-attachments/assets/f3c4283f-aa9f-478d-9647-e93a229f91ff)

Open IIS as an Admin

![image](https://github.com/user-attachments/assets/c131e988-b131-441c-810d-d063c2ee599c)















