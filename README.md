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

-Download? unzip the installation files
- Install / Enable IIS in Windows WITH CGI
- Register PHP from within IIS
- install VC_redist.x86.exe.
- Install SQL
- Install OS Ticket
- Assign Permissions
- Create ticket data base/session

<h2>Installation Steps</h2>


<img width="847" alt="image" src="https://github.com/user-attachments/assets/e74c852a-b118-4ea2-80aa-d69c03a37328" />

Download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder is named “osTicket-Installation-Files.
https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD The Files in this folder contain  installation files of  osTicket and some of the dependencies needed.

<<img width="644" alt="image" src="https://github.com/user-attachments/assets/e7070e6d-774f-4796-9844-84f50c0f692d" />

STEP BY STEP BREAK DOWN: 1) Download the folder 2) Go to downloads within the desktop files and locate osTicket-Installation-Files. 3) Place the file on the desktop, right click and select extract all. 


<img width="332" alt="image" src="https://github.com/user-attachments/assets/0c979bae-8eec-4b2b-9fb1-d04f51fe16e7" />

Enable IIS(web sever) with CGI by going to the control panel>programs>programs and features, click the IIS (internet information services) enable that. Then hit the drop box on world wide web services, aplication development features and lastly enable CGI.




<p>

  
  <img width="781" alt="image" src="https://github.com/user-attachments/assets/8e557e3a-3fba-43fa-bc2b-ca618a6b498e" />


From the “osTicket-Installation-Files” folder, install PHP Manager for IIS
Just double click the folder and agree to licensing agreement to complete the install.

From the “osTicket-Installation-Files” folder also install the Rewrite Module (rewrite_amd64_en-US.msi) with the same steps.
When you're installing osTicket, this module helps modify and redirect URLs so they look cleaner and work better for users and search engines.



Open the file explore and create a new file on the C: drive named PHP this Creates the directory C:\PHP. Next from the osTicket-Installation-Files extract the php-7.3.8-nts-Win32-VC15-x86.zip onto the new PHP folder you just created.


  
  (PHP Manager -> C:\PHP\php-cgi.exe)

<p>
<<img width="918" alt="image" src="https://github.com/user-attachments/assets/f5b62535-3a77-424d-90a0-ac46f33eeefd" />

</p>
<p>

Next you need to install VC_redist.x86.exe. from the osTicket-Installation-Files, also agreeing to the terms. Think of it like a toolbox that contains important parts needed for certain programs—like osTicket—to run properly on Windows.

<img width="376" alt="image" src="https://github.com/user-attachments/assets/34a515b6-87e7-4644-a3ae-afcf8404db70" />

After thats completed you need to install SQL. To do this you go back into the osTicket-Installation-Files and extract the (mysql-5.5.62-win32.msi). Click typical install, launch the my SQL configuration wizard and click standard configuration.
When it askl for the user name & password enter root for both (for the demonstration only). 
  
  
  
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

<img width="1345" alt="image" src="https://github.com/user-attachments/assets/4d3426b5-a568-4f87-841e-69f8cc3cb57b" />

<img width="724" alt="image" src="https://github.com/user-attachments/assets/b5f0ccd8-fa44-4f0c-a70d-39a84b604093" />

