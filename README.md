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

- Windows 10 Pro </b>

<h2> Familarize yourself with the osTicket System</h2>

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php </b>

End Users osTicket URL:
http://localhost/osTicket </b>

While logged in as an admin you are able to switch between Agent Panel and Admin Panel. In the admin panel you have more control and you can also configure settings if needed. 

<img src="https://i.imgur.com/nhB9CaA.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a></h2>

- Roles are the permissions granted to Agents per Department that they have access to. 
- While in the admin panel, let's configure Roles (for grouping permissions)
- Admin Panel -> Agents -> Roles
- Supreme Admin (this role has all the permissions enabled)

<img src="https://i.imgur.com/nzzVyGM.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/czDlnvg.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/7POOhiA.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/pOoogAO.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/ti9c3CW.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/4WBj1cf.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html">Departments</a></h2>

- Departments can help ticket visibility as well as separate tickets based on Departments such as Help Desk vs SysAdmins, vs Networking.
- Admin Panel -> Agents -> Departments
- SysAdmins

<img src="https://i.imgur.com/h1Vcn5w.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/cTARYsT.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/m2vXDDa.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/897Fhw9.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams</a> </h2>

- Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user.
- Admin Panel -> Agents -> Teams
- Online Banking

<img src="https://i.imgur.com/gUyzHTt.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/nOhBQgP.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/zgJOJE3.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agents</a> </h2>

- Agents are the workers who are given access to the help desk with the intent to respond and resolve the tickets.
- Admin -> Agents -> Add New

<img src="https://i.imgur.com/2evkMvp.png" height="80%" width="80%" alt=""/>

- Create new agent: Jane Doe
- Click on Set Password

<img src="https://i.imgur.com/7I3JI4M.png" height="80%" width="80%" alt=""/>

- Uncheck "Send the agent a password reset email" and "Require password change at next login"
- Create new password

<img src="https://i.imgur.com/wkfzwiv.png" height="80%" width="80%" alt=""/>

- Select Primary Department, in this case select "SysAdmins" and the "Supreme Admin" Role created earlier

<img src="https://i.imgur.com/DbrdcuA.png" height="80%" width="80%" alt=""/>

- Select the "Online Banking" Teams created earlier as well
  
<img src="https://i.imgur.com/oIvZNxh.png" height="80%" width="80%" alt=""/>

- Create another agent: John Doe

<img src="https://i.imgur.com/Au0ST1t.png" height="80%" width="80%" alt=""/>

- The primary department for this agent will be "Support" and have a "view only" which grants the agent to view tickets only.

<img src="https://i.imgur.com/nCBlnWp.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">Users</a></h2>

- Agent Panel -> Users -> Add New
- In some cases user registration is required to create tickets. It depends on how the ticketing system is setup and can be changed in User Settings.

<img src="https://i.imgur.com/zLdwF0H.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/Euocxw6.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/wobIRpt.png" height="80%" width="80%" alt=""/>

<h2>Configure  <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a></h2>

- SLA Plans or Service Level Agreements are to provide a length of time in which the help desk administrator expects tickets to be closed.
- Admin Panel -> Manage -> SLA

<img src="https://i.imgur.com/xipzl3q.png" height="80%" width="80%" alt=""/>

- Sev-A (Grace period: 1 Hour, Schedule: 24/7)

<img src="https://i.imgur.com/VxB68cF.png" height="80%" width="80%" alt=""/>

- Sev-B (Grace period: 4 Hours, Schedule: 24/7)

<img src="https://i.imgur.com/IPynPNx.png" height="80%" width="80%" alt=""/>

- Sev-C (Grace period: 8 Hpurs, Business Hours)

<img src="https://i.imgur.com/OIpCTmZ.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html">Help Topics</a></h2>

- Help Topics ensure proper assignment and prompt response to the ticket. Help Topics determine what Department the ticket is routed to which also determines which Agents have access to the ticket.
- Admin Panel -> Manage -> Help Topics

<img src="https://i.imgur.com/CRSIaT0.png" height="80%" width="80%" alt=""/>

- Business Critical Outage

<img src="https://i.imgur.com/D58KPFv.png" height="80%" width="80%" alt=""/>

- Personal Computer Issues

<img src="https://i.imgur.com/GVfGYZ6.png" height="80%" width="80%" alt=""/>

- Equipment Request

<img src="https://i.imgur.com/e8Tq5fd.png" height="80%" width="80%" alt=""/>

- Password Reset

<img src="https://i.imgur.com/MqMHYmT.png" height="80%" width="80%" alt=""/>

- Other

<img src="https://i.imgur.com/qA3yz0p.png" height="80%" width="80%" alt=""/>

<h2>Additional Steps</h2>

- Make sure the SysAdmins Department is set to a "Top Level Department"
- Delete the Maintenance Department
- Admin Panel -> Departments -> Select Maintenance -> Click on More and Delete

<img src="https://i.imgur.com/Pf3qTly.png" height="80%" width="80%" alt=""/>










