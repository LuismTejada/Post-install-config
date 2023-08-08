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

After we created the new team, we will now create a new setting that will allow anyone to create tickets. To do so just follow the instructions, Admin Panel-> Setting -> Users. Make sure "Require registration and login to create tickets" is turned off.

<img width="1280" alt="Screen Shot 2023-08-08 at 10 53 26 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/9ad5c190-eb26-4f52-bc52-30a67e708707">


The next step is creating employees, in this case, they are call agents. The employees are the ones in charge of working on the tickets and solving them. This agent will have limited access, they can also have different roles depending on the department they are in. You will have to click Permission -> Access -> Teams. We will create two random users and their names will be Jane Doe and John Doe. 

<img width="1280" alt="Screen Shot 2023-08-08 at 11 04 41 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/f3584f70-3b9e-4672-aaca-4eea0e347e5a">

<img width="1280" alt="Screen Shot 2023-08-08 at 11 09 54 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/fae46503-88b9-4f6d-8bdb-e17c0fa1ab9d">

The next step is creating users. Users are going to be our customers, who created tickets when they are having issues. A user is identified with their email address. To create a user go to Agent Panel -> Users -> User Directory -> Add User.

<img width="1280" alt="Screen Shot 2023-08-08 at 11 19 48 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/ba4e894c-368f-4b6f-818a-eec0f7d7d0db">

<img width="1280" alt="Screen Shot 2023-08-08 at 11 20 30 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/cbb9a330-9dfd-47a6-ad7e-3b0125a6dde8">

SLA or Service Level Agreement plans to provide the length of time the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to the Admin Panel -> Manage -> SLA Plans. Each SLA has a different time limit. This screen shows an SLA plan called "SEV-A" that has a 24/7 schedule and a one-hour grace period. Make two others 

<img width="1280" alt="Screen Shot 2023-08-08 at 11 44 26 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/d538a055-b673-429d-a687-c3c97bb1797e">

<img width="1280" alt="Screen Shot 2023-08-08 at 11 45 06 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/1b183c31-2180-44da-bc87-763420309385">

Help topics help the user categorize their tickets. We are going to create 4 categories(Business Critical; Personal computer Issue; Equipment issue; & Password Reset) for the end users to utilize when reporting an issue  

<img width="1280" alt="Screen Shot 2023-08-08 at 11 55 12 AM" src="https://github.com/LuismTejada/Post-install-config/assets/140201562/88a94024-63bb-4a3b-9fe2-3714afa8f3d5">


</p>
<br />
