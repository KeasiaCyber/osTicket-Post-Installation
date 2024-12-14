# osTicket-Post-Installation
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/z3pxapT.png" height="80%" width="80%" alt="Steps 1"/>
</p>
<p>
We have successfully set up osTicket, and now we’ll move on to system administration and post-installation tasks. The first step is to configure new roles within the help desk. To do this, navigate to Admin Panel → Agents → Roles. Click on "Add New Role", then enter the name of the role you want to create. In this case, we will create a Supreme Admin role. You can also modify the permissions for specific roles. Since this is a Supreme Admin role, you will assign it all permissions. Keep in mind that roles determine an agent’s permissions, so not all agents will have unlimited access. If you’ve followed the steps correctly, your screen should display the newly created "Supreme Admin" role, confirming its successful addition to the system.
</p>
<br />

<p>
<img src="https://imgur.com/IBYzdCy.png" height="80%" width="80%" alt="Steps 2"/>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab too.
</p>
<br />

<p>
<img src="https://imgur.com/33rm7ig.png" height="80%" width="80%" alt="Steps 3"/>
</p>
<p>
After configuring a new department, the next step is to set up a team. Teams enable you to gather agents from various departments, allowing you to create specialized groups, such as an A team with top technicians from different areas. For example, you can create a help topic related to a product you offer and assign it to a team of agents who specialize in that product. To set up a team, go to Agents → Teams. A Level I support team is created by default, and in this case, we will create an Online Banking Team.
</p>
<br />

<p>
<img src="https://imgur.com/u4d9bqx.png" height="80%" width="80%" alt="Steps 4"/>
</p>
<p>
Now it’s time to create agents, who are the employees responsible for resolving tickets in the helpdesk. Agents are assigned a primary department and role for tickets directed to their department, but they can also be granted access to other departments and assigned different roles based on the department they are in. Permissions, access, and team assignments are managed in the Agents tab.
</p>
<br />

<p>
<img src="https://imgur.com/WxbOgTb.png" height="80%" width="80%" alt="Steps 5"/>
</p>
<p>
After creating agents, the next step is to create users, who are customers that submit tickets when facing issues. A user is identified by their email address. To create a user, navigate to Agent Panel → Users → User Directory → Add New.
</p>
<br />

<p>
<img src="https://imgur.com/WgV85ul.png" height="80%" width="80%" alt="Steps 6"/>
</p>
<p>
SLA Plans define the expected time frame within which the help desk should resolve a specific ticket. To create SLA Plans, go to Admin Panel → Manage → SLA Plans. Each SLA includes a schedule, which also specifies a grace period. For example, SEV-A has a 24/7 schedule with a one-hour grace period.
</p>
<br />

<p>
<img src="https://imgur.com/2NsW1go.png" height="80%" width="80%" alt="Steps 7"/>
</p>
<p>
Help topics help users categorize their tickets. In the example above we have made a help topic for "Business Critical Outage" this can be for customers cannot access mobile banking.
</p>
<br />
