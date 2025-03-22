# osticket-prereqs


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

- PHP manager
- Rewrite Module
- MySQL
- VC Redist
- PHP

<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/5792cadf-9fe1-44e4-9e76-38e1cb7aaecb)


</p>
<p>
 - Enable IIS in Windows WITH CGI

</p>
<br />


![image](https://github.com/user-attachments/assets/74e6df73-14d2-4255-8d88-badae4de0926)

</p>
<p>
 - Download everything in the folder
</p>
<br />


![image](https://github.com/user-attachments/assets/b6ac61a9-b28a-4af0-98ad-175539406f2b)

</p>
<p>
 - Set password in MySQL
</p>
<br />


![image](https://github.com/user-attachments/assets/4f24f944-0259-4461-9d70-a2cc25bdb2c6)

</p>
<p>
 - Register new PHP from IIS and reload the server
</p>
<br />

![image](https://github.com/user-attachments/assets/a5651139-54ae-489c-b56c-04719f00af90)

</p>
<p>
 - From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”
 - Reload the server
</p>
<br />

![image](https://github.com/user-attachments/assets/7b4b6b9e-2786-40e6-b125-c8c3928b73b1)

</p>
<p>
Go to sites -> Default -> osTicket
On the right, click “Browse *:80” to open up OsTicket

</p>
<br />

