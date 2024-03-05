# Osticket-Prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Resource Group
- Create Azure VM (Virtual Machine)
- Download (microsoft remote desktop) mac users
- Enable Internet Information Services (IIS)
- Confirm Installed Correctly 
  


<h2>Installation Steps</h2>

To get started with the OSticketing Lab the first steps are to create your resource group which as you can see in the picture below i created my resource group with name of RG-osticket, And then after creating the resource group i created my virtual machine listed as VM-osticket.


<img width="520" alt="Screenshot 2024-03-05 at 12 29 36 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/46489525-a156-4c39-9ebb-d4ac06b6bf61">
<p>

</p>
<p>
After the resource group is created as well as the vm, im going to copy the ip address as you can see below and then use my Microsoft Remote Desk top to log into the VM and then begin to start to downlaod the prerequisites on the VM.
</p>
<img width="539" alt="Screenshot 2024-03-05 at 12 41 19 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/b1b92054-628c-4b47-b901-e286a866c462">

After logging into VM, I then proceeded to install all prerequisites starting with installing and enabling IIS (Internet Information Services) (also know as a web server that allows this computer to serve up websites like the Os ticketing system because it runs out of a website) were installling with Windows C with CGI.

<p><img width="539" alt="Screenshot 2024-03-05 at 1 10 57 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/79368a07-0b12-49b8-ab00-bf4503fa8e83">
  
<img width="536" alt="Screenshot 2024-03-05 at 1 17 37 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/16c86de4-dd7d-4207-9db6-d9c2b216519b">

<img width="542" alt="Screenshot 2024-03-05 at 1 19 49 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/bd694f1e-a2a6-4ad0-8836-67a99b2c8355">

After Instalation is complete you want to test it by going to a web browser on the VM to make sure the downlaod was completed by entering in 127.0.0.1 into the search bar. *Key Note* You want to make sure you see the blue Internet Information Services screen comes up to make sure its downloaded correctly.


<img width="542" alt="Screenshot 2024-03-05 at 1 26 13 PM" src="https://github.com/Cwaters24/Osticket-Prereqs/assets/147946985/4f5d391e-a723-49c5-93b1-e47a6a03fa9a">


