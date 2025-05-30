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

- Install/ Enable ISS in Windows WITH CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Install MySQL
- Install osTicket v1. 15.8
- Install HeidiSQL
  
<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/9f0dbc34-a39d-4acb-a309-812a44e14882)
![image](https://github.com/user-attachments/assets/2463a092-899b-407a-bf7c-712d5b7a906f)
![image](https://github.com/user-attachments/assets/54e1101f-4406-4fc2-a916-e220ab0fbcc2)

<p>
</p>
<p>
 After setting up my virtual machine, I enabled IIS along with CGI support. To verify that the web server was running, I opened Microsoft Edge and navigated to the loopback address (127.0.0.1). Above are the results before and after enabling the web server.


</p>
<br />


 ![image](https://github.com/user-attachments/assets/39be7c7f-8eaa-46c2-9939-cb6149b2f0d5)



<p>
</p>
<p>
I installed MySQL 5.5 to serve as the backend database for storing critical application data, including user accounts, ticket information, and other related records.
</p>
<br />

<p>

  

  ![image](https://github.com/user-attachments/assets/a4d6d1db-0141-41df-96d8-6f6d076d92a5)


</p>
<p>
This is the final result of the steps outlined above: osTicket has been successfully installed, and a test ticket has been created to confirm functionality.
</p>
<br />
