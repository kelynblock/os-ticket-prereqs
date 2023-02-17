# os-ticket-prereqs<p align="center">

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

- Enable Internet Information Services (IIS)

- Install PHP

- Install MySQL

- Install osTicket

- osTicket Help desk

<h2>Installation Steps</h2>

<p>

<img src="https://i.imgur.com/gTm5egg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

After connecting to Azure VM via RDP, Right-Click Start menu >Run >Control (opens control panel) >Programs >Turn Windows Features on/off >Check the IIS box & expand> Check World Wide Web box >Application Dev Features >Check CGI box >OK.

</p>

<br />

<p>

<img src="https://i.imgur.com/L3ZUudl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Install PHP Manager and all dependencies. Created a PHP directory in the c: drive and extracted PHP files & their contents into this directory.

</p>

<br />

<p>

<img src="https://i.imgur.com/Zukia2O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Install MySQL, a database that osTicket relies on.

</p>

<br />

<p>

<img src="https://i.imgur.com/ta6fBCh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Install osTicket. Enabled extensions, edited permissions, setup osTicket in browser and installed HeidiSQL. HeidiSQL allows you to connect to MySQL server and setup a database for osTicket to use.

</p>

<br />

<p>

<img src="https://i.imgur.com/nnnHPOl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

osTicket setup and running. Logged in with the credentials entered during the actual setup.

</p>

<br />
