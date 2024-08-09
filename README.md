<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11

<h2>Post-Install Configuration Objectives</h2>

- Install/Enable IIS with CGI
- Install PHP Manager for IIS
- Install Rewrite Module
- Install VC redist.x86.exe
- Install MySQL
- Install osTicket

<h2>Configuration Steps</h2>

![Screenshot 2024-08-08 103133](https://github.com/user-attachments/assets/3b55a92d-f19e-44d5-a349-edf35788a0fa)


</p>
<p>
In this step I installed IIS with CGI.  From the control panel, you go to Turn Off Windows Features ON and OFF.  From there you find Internet Information Services then Application and Developement features and enable CGI.
</p>
<br />

![Screenshot 2024-08-08 103739](https://github.com/user-attachments/assets/6af3aac4-8288-449d-8cc7-82b5c1df3ef1)

In the screenshot above you can see that I downloaded and installed PHP Manager. 
</p>
<br />

<p>

![Screenshot 2024-08-08 104028](https://github.com/user-attachments/assets/d57e8b7b-44b2-4b6b-8a8a-0bfb529bd95f)

Here I'm installing the Rewrite Module or the rewrite_amd64_en-US.msi.
</p>
<br />

![Screenshot 2024-08-08 105530](https://github.com/user-attachments/assets/7240369b-8327-4227-8698-e469b7f9c0b8)

In this next step I downloaded and installed VC_redist.x86.exe. or C++. 


![image](https://github.com/user-attachments/assets/84e236d3-43de-4c1b-a87d-7932063d50ae)

This following step, MySQL was downloaded and installed. 


![image](https://github.com/user-attachments/assets/79e7044c-0879-4b2b-b44f-c3b99701c80b)

Here you can see were are in the final instalation steps setting up help desk name, username, and password.


