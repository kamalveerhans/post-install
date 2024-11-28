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

- Configure Roles(grouping Permissions), Departments, Teams, Agents(workers), Users(customers), SLA, Help Topics(for when users create a ticket).

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/GhAfCfC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added A new role named Supreme Admin, allowing all permisions
</p>
<br />

<p>
<img src="https://imgur.com/l9ha4u8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
</p>
<br />

<p>
<img src="https://imgur.com/MVgI47Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Teams(Pull Agents from different Departments) 
</p>
<br />
<p>
<img src="https://imgur.com/2mWlbJZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

</p>
<br />
<p>
<img src="https://imgur.com/1lSX61D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Agents Jane (Dept: SysAdmins) John (Dept: Support)
</p>
<br />
<p>
<img src="https://imgur.com/sLON3Kk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Users( Karen and Ken) 
</p>
<br />
<p>
<img src="https://imgur.com/1kjL3nM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured SLA Sev-A (Grace Period: 1 hour, Schedule: 24/7), Sev-B (Grace Period: 4 hours, Schedule: 24/7), Sev-C (Grace Period: 8 hours, Business Hours)

</p>
<br />
<p>
<img src="https://imgur.com/vXpg45e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Help Topics Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other

</p>
<br />
