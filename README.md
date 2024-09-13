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

- Enable Internet Information Services
- Install Web Platform 
- Install C++ / Redistributable
- Configure Permissions/ Enable Extensions
- Install osTicket

<h2>Installation Steps</h2>

![6AAE6010-0229-4F27-9079-FBC36C2F5A8C_1_201_a](https://github.com/user-attachments/assets/cc10470d-188d-4d8d-8a94-fd8a077220fc)





Virtual Machine has been created in our azure portal. All work will be conducted within our Windows 10 Virtual Machine
</p>
<br />

![image](https://github.com/user-attachments/assets/7d1f3a2b-63a8-4998-a234-430deca81516)

Within the VM osTicket-Installation-Files are downloaded and unzipped onto the desktop.
IIS is installed / enabled in Windows WITH CGI


</p>
<br />

![378E6483-A79B-4F24-B117-ABD9DEA9A81E](https://github.com/user-attachments/assets/d8254662-184c-4455-8f8f-acf7c8d72658)


Proceed to install PHP Manager for IIS, Rewrite Module,  MySQL 5.5.62 , and Redistributables. After successful completion of all installations, we may register PHP from within IIS and install osTicket. 

As seen in the screenshot above, a few extensions are not enabled. From within PHP manager we are able to enable our extensions.


</p>
<br />

![C5DB725B-B5F8-40C5-9219-7E87167D2848](https://github.com/user-attachments/assets/36f3a89d-ad45-4a1d-a90a-87d00eb093eb)


Lastly, osTicket is set up in our Browser. We are to Proceed to Install HeidiSQL, including installation of osTicket database. After our database is completed we can finalize installation in MYSQL and “click Install Now!”
