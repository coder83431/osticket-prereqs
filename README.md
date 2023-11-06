<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1> Prerequisites and Installation of osTicket Deployed in the Cloud (Azure) </h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (version 22H2)

<h2>List of Prerequisites</h2>

- Microsoft Web Platform Installer
- OsTicket V1.15.8
- HeidiSQL

<h2>Installation Steps</h2>


<p>  
<img src = "https://i.imgur.com/FoDQra2.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>Overview</p>

<p>
<img src = "https://i.imgur.com/GFYFR0R.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <p>
1. Create a resource group in Azure.
</p>                                                                                                    
                                                                                                     
<p>
<img src= "https://i.imgur.com/Pk3J6Rk.png" " height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

<p>
                                                                                                 
                                                                                                 
                                                                                                 
2. Create a virtual machine within Azure. When configuring the virtual machine, make sure to have it configured to be within the resource group that was previously made.
</p>
<br />

<p>
<img src="https://i.imgur.com/dDY9AQi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Open Remote Desktop. Here, you can type in the username and password when you initially made the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/PB1vmBe.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Install/ Enable IIS (Internet Information Services). Windows Control Panel < Programs and Features.
</p>
<br />

<p>
<img src="https://i.imgur.com/yt4ZPAk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Install "Microsoft Web Platform Installer". Add "MySQL 5.5" and all simple versions of X86PHP up until 7.3
</p>
<br />

<p>
<img src="https://i.imgur.com/8ob8uQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Install osTicket v1.15.8.
</p>
<br />

<p>
<img src="https://i.imgur.com/SbhSS6V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Go Back To IIS, Sites->Default->osTicket, Double click PHP Manager, Enable PHP_imap.dll, Enable PHP_intl.dll, Enable PHP_opcache.dll.
</p>
<br />

<p>
<img src="https://i.imgur.com/wVSvcC6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Rename the File To OST-Config.PHP And Assign Permissions To the File.
</p>
<br />

<p>
<img src="https://i.imgur.com/U0zZqC1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Continue Setting Up OsTicket In Browser.
 
- Name Help Desk
- Add Default Email

</p>
<br />

<p>
<img src="https://i.imgur.com/IdTzZWd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Download And Install HeidiSQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/0LOpcLJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
11. OsTicket Is Ready. 
</p>
<br />
