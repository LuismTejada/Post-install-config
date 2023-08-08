# osTicket-Post-Installation-Configuration
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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure agents
- Configure Users
- Configure SLA's 
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
</p>
We have finally configured osTicket from nothing in the previous lab. Now this one is going to be a little different, we are going to be doing a post-installation setup. The first step is going to configure new roles within the help desk. In order to this go to Admin Panel -> Agents -> Roles. In the Admin Panel, we will be creating a "Supreme Admin". Click on "Add new" -> "Role" After you will enter the name for the admin, in our case is"Supreme Admin". In this window, you can modify any specific roles and permission. In our case, our admin will have all the permissions. But just keep in mind that not all agents are going to have all the permissions. After you grant access to all the permissions your screen will look like this.

<img width="1280" alt="Screen Shot 2023-08-08 at 7 19 12 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/5809458e-63d7-4dcc-86aa-2e4fbad5795a">

</p>
<br />

<p>
The next step is creating a Department. Click on "Departments"->"Add New Department" and the name for the new Department is "System Administrators" this is where the "Supre Admin" will be designated.
  
<img width="1280" alt="Screen Shot 2023-08-08 at 7 33 31 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/9bec5028-8de0-47ac-9e6e-f7a1e7abf487">

<p>
After making a new department we will set up a new team. Teams allow you to pull agents from different departments. Teams allow you to pull agents from different departments and organize them to handle a specific issue or user via Help Topic or Ticket Filter. You go to Agents-> Teams. A Level I Support team has already been made by default. After clicking on "Add New Team" name it "Level II Support".
  
<img width="1280" alt="Screen Shot 2023-08-08 at 7 51 16 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/20e1b836-6612-4a3d-b773-7c7bc39df268">

  
</p>
<br />
