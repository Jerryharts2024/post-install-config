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

<br />

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
<br />

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
Team ensures that the osTicket has the capabilites of pulling agents from different departments and organize them in the way they can handle a specific issue or user via a Help Topic or Ticket Filter. 
 To create a Team in your Admin Panel, locate the Agents tab, and click on Teams. Then click Add New Team on the right, and fill out the appropriate information. Then you will be able to add Agents to the team by clicking on their name from your list of Agents and checking the corresponding box next to the Team name you wish to add them at the bottom of the page. </p>
 
 Practically click on --> Admin Panel --> Agents --> Add New Team.. Assign a name to the team, such as "Level I Support" and add members to the teaams. This will ensure agents work together
</p>
<br />

<h3>Step 4:  Configure Settings to - Allow anyone to create tickets</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/234027782-fe3a8061-b097-4c86-a216-97e9e02db993.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
This section allows you to create standards and rules for each user when ticket is created on the Help Desk. this helps to prevent random tickets and also it increases user accessibility level in the help desk. Here you can decide if registration is required for  end users before creating a ticket or otherwise. <br />
To configure this section, go to --> Admin Panel --> Settings --> User Settings  check --> Registration Required: Require registration and login to create tickets then --> save changes
</p>
<br />

<h3>Step 5: Configure Agents (workers)</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/234033821-8ee99469-c231-4676-9cd9-10e240e2ff76.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
Agents are basically someone who would respond and resolve tickets. So ensure that the help desk functions appropriately we have to give access to agents by assigning an agent to a primary department and given a Primary Role for the Tickets/Tasks routed to that department. The role of an agent can also be extended to other department by given them access to that department. 
 To create an Agent, Admin Panel --> Agents --> Add New. 
 </p>
<br />

 <h3>Step 6: Configure Users (customers)</h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/234054657-84e63bb2-200c-4d94-9a31-3d11adbd22a8.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
 Users are ticket owners or creator of ticksts in the help desk. This section allows us to create end users. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk. These users can as well be added or deleted from the directory.  Since users are associated to there email and ticket, deleting a user means you must also delete the ticket.
To create a user, go to --> Agemt Panel --> User --> Add user
 </p>
<br />
 
  <h3>Step 7: Configure SLA </h3>
<p>
<img src="https://user-images.githubusercontent.com/131130119/234063168-f7dee7e6-bfbe-48fb-b0ac-bddcde4ccc96.png" height="80%" width="80%" alt="osTicket - Post-Install Configuration"/>
</p>
<p>
SLAs otherwise know as Service Level Agreements provide the length of time in which the help desk Administrator expects tickets to be closed. This basically refers to the standard of service a customer can expect when working for my company.
It lays out what I can provide my customer as well as the timeline within which I will be delivering their services. 
 <br />
 To create SLAs --> Admin Panel -> Manage -> SLA --> Add New SLA Plan
 

 
 </p>
<br />
