<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. This osTicket system was installed on a virtual machine running Windows 10 with Microsoft Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows with CGI
- PHP Manager for IIS
- MySQL
- osTicket Installation Files
- HeidiSQL

<h2>Installation Steps</h2>


<p>

![IIS Pic](https://github.com/user-attachments/assets/5d8f8b49-d262-4402-8186-fe17e9a3a62d)


</p>
<p>
  
IIS stands for Internet Information Services. It is a Microsoft web server that is used to exchange web content between users over the internet. The computer becomes a webserver which is essential to run a ticketing system. 

<br />

<p>
  
![image](https://github.com/user-attachments/assets/443db774-9390-4a46-a532-5e1bab633e11)
![PHP Manager Pic2](https://github.com/user-attachments/assets/cbe0e30e-4192-4fbe-ab86-67631287f3eb)

  
</p>
<p>
PHP is a backend webserver language that osTicket uses to run and needs to be installed with features enabled for osTicket to run smoothly.
  

</p>
<br />

<p>
  
![MySQL pic](https://github.com/user-attachments/assets/518b56c1-07f7-4350-bbf7-0b0a73b11668)
  
</p>
<p>
MySQL 5.5.62 is installed. It is a database that osTicket will use to store data, it will store everything from user accounts to ticket information. A database is needed in order for osTicket to run.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/22d850c2-34de-45d9-b610-77119863d2a5)
  
</p>
<p>
There are a fair number of prerequisites required in order to install osTicket and to make sure it runs properly. Everything after is just adding the final touches to the setup of osTicket.  
  
</p>
<br />
<p>
  
![HeidiSQL Pic](https://github.com/user-attachments/assets/10d92d76-1d3d-46bb-9791-380f936ae1d6)
  
</p>

<p>
Heidi SQL is installed. A database has already been installed above but we need to be able to connect to that database. In order to connect to the databese Heidi SQL is installed and given the credentials inorder to access the database that osTicket will use.
</p>
<br />

<p>
  
![osTicket Installed Pic](https://github.com/user-attachments/assets/0942760a-2b87-4014-b79c-751b7201082f)
  
</p>
<p>
  
This concludes the setup of osTicket, this was a very high level overview of the steps taken to install and setup osTicket. There are more steps involved and more applications needed to be downloaded on the backend to make sure osTicket runs smoothly.
</p>
<br />
