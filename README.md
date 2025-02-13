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

While logged in as an admin you are able to switch between Agent Panel and Admin Panel. In the admin panel you have more control and you can also change or configure settings if needed. 

<img src="https://i.imgur.com/nhB9CaA.png" height="80%" width="80%" alt=""/>

<h2>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a></h2>

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

- Admin Panel -> Agents -> Teams (pulls agents from different Departments)
- Online Banking

<img src="https://i.imgur.com/gUyzHTt.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/nOhBQgP.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/zgJOJE3.png" height="80%" width="80%" alt=""/>

