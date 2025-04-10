<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows WITH CGI
- Register PHP from within IIS 
- Install OS Ticket
- Assign Permissions


<h2>Installation Steps</h2>
<<img width="644" alt="image" src="https://github.com/user-attachments/assets/e7070e6d-774f-4796-9844-84f50c0f692d" />



From the “osTicket-Installation-Files” folder, install PHP Manager for IIS 
From the “osTicket-Installation-Files” folder install the Rewrite Module 
Create the directory C:\PHP
with in the contoll panel enable IIS in Windows WITH CGI

<p>

  
  <img width="781" alt="image" src="https://github.com/user-attachments/assets/8e557e3a-3fba-43fa-bc2b-ca618a6b498e" />


  
  (PHP Manager -> C:\PHP\php-cgi.exe)

<p>
<<img width="918" alt="image" src="https://github.com/user-attachments/assets/f5b62535-3a77-424d-90a0-ac46f33eeefd" />

</p>
<p>
From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”

</p>
<br />

<p>
<img width="1295" alt="image" src="https://github.com/user-attachments/assets/d125f741-1e1d-43a1-aef9-d610802d81d5" />

</p>
<p>
From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”

<br />
<img width="868" alt="image" src="https://github.com/user-attachments/assets/8f765430-ed2c-45e1-a129-6078a433428b" />

Permissions added to everyone (not best practice)

