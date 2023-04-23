<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
<p>
After installation, osTicket requires additional configuration through the admin interface or panel before it is entirely functional. Access to the admin panel is restricted to employees with admin rights. The post-installation configuration basically comes down to customizing departments, staff members, agents, hot topics, emails, and system preferences. Please note that the post-installation configuration requires you to log in with the username and password you created during installation. so in this project we are going to...
</p>

- configure roles
- create departments
- configure teams
- configure system preferences to allow ticket creation
- configure users (customers)
- configure SLAs
- configure hot topics


<h2>Configuration Steps</h2>

<p>
<img src="https://user-images.githubusercontent.com/131130119/233841551-6e4146d4-c5d0-4b39-8f17-575d86d3b36f.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
This is the first page you see after logging into the osTicket admin panel
</p>

<h3>Step 1: Configure Roles</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/233842402-6fc49201-491e-4e44-b573-24c007f97f9b.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
Roles enable agents to have access to a particular department. So basically the are permission level granted to agents.
to creat and configure roles simply click on --> Admin Panel --> Agents --> Roles and --> Add New Role --> assign the role a name. example "Supreme Admin". 
 --> Add permssion. Permissions allow agents control within the help desk which are not Department specific access items.
</p>

<h3>Step 2: Configure Departments</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/233845086-8e58ed8e-ae15-4794-947e-cef8581e6864.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
 Departments allow the osTicket to route ticket in the help desk, each Department comprises of many setting.
To creat and configure department simply click on --> Admin Panel --> Agents --> Departments and --> Add New Department. Assign a name to the department. You can clearly see that there are many settings associated with the departmeent.
</p>
<br />

<h3>Step 3: Configure Teams</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/233846758-7c8ba934-e143-489c-b58e-d68ae2c257a2.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
Team ensures that the osTicket has the capabilites of pulling agents from different departments and organize them in the way they can handle a specific issue or user via a Help Topic or Ticket Filter. To add new department click on --> Admin Panel --> Agents --> Add New Team.. Assign a name to user, such as "evel I Support" and add members to the teaams. This will ensure agents work togethr
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
