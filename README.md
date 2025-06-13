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

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/tLnXBDQ.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before installing osTicket, I created a Virtual Machine using Azure. This allows me to log in into a Windows Remote Desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/8ApnbXV.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this process, I download and install the following applications: PHP Manager, Rewrite, VC, MySQL, and Heidi SQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/BIPpy6N.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To activate IIS or Internet Information Services for osTicket to work, I go through the Control Panel and run it as an Admin, accessing Programs to get to Internet Information Services then to CGI. CGI enables osTicket to display information based on user input.
</p>
<br />

<p>
<img src="https://imgur.com/cnHTxMk.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Proof the IIS has been activated.
</p>
<br />

<p>
<img src="https://imgur.com/drBah8h.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open and install MySQL. This program will aid in storing user information, departments, and system settings.</p>
<br />

<p>
<img src="https://i.imgur.com/ugSz1J9.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order for osTicket to fully work, I go through the PHP Manger and enable a few PHP extensions; imap, intl, and opcache.
<br />

<p>
<img src="https://i.imgur.com/9fVvDtm.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before completely being done, we have to set up our databases and connect them to each other, MySQL and HeidiSQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/5ic8TJD.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, after all the installing and enabling and clicking on Browse *:80 (http). This take us to Support Center Ticketing System where one is to create an username and password.
</p>
<br />
