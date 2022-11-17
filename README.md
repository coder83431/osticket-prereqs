<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation </h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (version 22H2)

<h2>List of Prerequisites</h2>

- Microsoft Web Platform Installer
- OsTicket V1.15.8
- HeidiSQL

<h2>Installation Steps</h2>

<p>
<blockquote class="imgur-embed-pub" lang="en" data-id="a/zXbKNQy" data-context="false" ><a href="//imgur.com/a/zXbKNQy"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>   
</p>

<p>
<img src="https://i.imgur.com/pYxfVoR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Create a virtual machine within Azure.
</p>
<br />

<p>
<img src="https://i.imgur.com/g0E8vs1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Open Remote Desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/GmSUX3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Install/ Enable IIS (Internet Information Services).
</p>
<br />

<p>
<img src="https://i.imgur.com/yt4ZPAk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Install "Microsoft Web Platform Installer".
      - Add "MySQL 5.5"
      - Add All Simple Versions Of X86PHP Up Until 7.3
</p>
<br />

<p>
<img src="https://i.imgur.com/8ob8uQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Install osTicket v1.15.8.
</p>
<br />

<p>
<img src="https://i.imgur.com/SbhSS6V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Go Back To IIS, Sites->Default->osTicket, Double click PHP Manager, Enable PHP_imap.dll, Enable PHP_intl.dll, Enable PHP_opcache.dll
</p>
<br />

<p>
<img src="https://i.imgur.com/wVSvcC6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Rename File To OST-Config.PHP And Assign Permissions To File.
</p>
<br />

<p>
<img src="https://i.imgur.com/U0zZqC1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Continue Setting Up OsTicket In Browser.
  -Name Help Desk
  -Add Default Email
</p>
<br />

<p>
<img src="https://i.imgur.com/IdTzZWd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Download And Install HeidiSQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/0LOpcLJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Congratulations! OsTicket Is Ready. 
</p>
<br />
