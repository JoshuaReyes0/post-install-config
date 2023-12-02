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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/aHHovwg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/poB9iN4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JaL6GsQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles:

  - Access Admin Panel -> Agents -> Roles.
  - Create a role named "Supreme Admin."
</p>
<br />

<p>
<img src="https://i.imgur.com/FNai7DA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/OKYPwYh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments:

  - Access Admin Panel -> Agents -> Departments.
  - Create a department named "System Administrators."
</p>
<br />

<p>
<img src="https://i.imgur.com/yQepwRA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/fafk95H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams:

  - Access Admin Panel -> Agents -> Teams.
  - Create teams named "Level I Support" and "Level II Support."
</p>
<br />
<p>
<img src="https://i.imgur.com/y4NUxUH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow Ticket Creation:

  - Access Admin Panel -> Settings -> User Settings.
  - Set "Registration Required" to require registration and login to create tickets.
</p>
<br />
<p>
<img src="https://i.imgur.com/iK7RE52.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/OvpkYvE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (Workers):

  - Access Admin Panel -> Agents -> Add New.
  - Add agents: Jane and John.
</p>
<br />
<p>
<img src="https://i.imgur.com/GnomLei.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MB0D1rf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (Customers):

  - Access Agent Panel -> Users -> Add New.
  - Add users: Karen and Ken.
</p>
<br />
<p>
<img src="https://i.imgur.com/SKPBBTx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/I4Vmu16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA (Service Level Agreements):

  - Access Admin Panel -> Manage -> SLA.
  - Create SLA levels:
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
</p>
<br />
<p>
<img src="https://i.imgur.com/CRnkGBG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics:

  - Access Admin Panel -> Manage -> Help Topics.
  - Create help topics:
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset.
</p>
<br />
