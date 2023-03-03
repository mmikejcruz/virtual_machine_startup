# virtual_machine_startup
Creating A Virtual Machine through Azure Networks 
<p align="center">
<img src="https://i.imgur.com/shXFZUv.png"/>
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

- Enabe IIS with CGI
- Install Rewrite Module
- Download PHP 7.3.8 and unzip content into directory
- Install MySQL and launch configuration wizard with a typical setup
- Register PHP from within IIS as an admin

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/9I5i7SO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Run Control Panel and under programs click features on or off. Through Internet Information Services, expand World Wide Web and under Application Development features turn CGI on.
</p>
<br />

<p>
<img src="https://i.imgur.com/aSslbBh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install IIS URL REWRITE MODULE 2. This enables Web administrators to create powerful rules to implement URLs that are easier for users to remember and easier for search.
</p>
<br />

<p>
<img src="https://i.imgur.com/MUOz9dh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the directory c://php and unzip all the content included in file PHP 7.3.8 there. Allows for PHP Manager to be registered within IIS as an admin. MySQL is installed to have a database for osTicket to store their application data.
</p>
<br />
