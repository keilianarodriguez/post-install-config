<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
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

Configure Roles:

Accessed the Admin Panel and navigated to Agents -> Roles. Created a role named "Supreme Admin".

<p>
<img src="https://imgur.com/w53j0Bm.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/zrBqqZf.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/2DvCvjj.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<br />

Configure Departments:

Accessed the Admin Panel and navigated to Agents -> Departments. Created a department named "System Administrators".

<p>
<img src="https://imgur.com/gKG92ew.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

</p>



Configure Teams:

Accessed the Admin Panel and navigated to Agents -> Teams. Created two teams named "Level I Support" and "Level II Support".
<p>
<img src="https://imgur.com/2itpRUv.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

</p>




<br />

Allow Anyone to Create Tickets:

Accessed the Admin Panel and navigated to Settings -> User Settings. Set "Registration Required" to require registration and login to create tickets.
<p>
<img src="https://imgur.com/jjU2gzY.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<br />

Configure Agents (Workers):
 
Accessed the Admin Panel and navigated to Agents -> Add New. Added two agents named "Jane" and "John".
<p>
<img src="https://imgur.com/kKvNAqv.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>



Configure Users (Customers):

Accessed the Agent Panel and navigated to Users -> Add New. Added two users named "Karen" and "Ken".
<p>
<img src="https://imgur.com/B9zD8UB.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>


Configure SLA (Service Level Agreement):
Accessed the Admin Panel and navigated to Manage -> SLA. Configured three SLAs: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours).

<p>
<img src="https://imgur.com/puaXVkK.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>


Configure Help Topics:

Accessed the Admin Panel and navigated to Manage -> Help Topics. Configured several help topics including "Business Critical Outage", "Personal Computer Issues", "Equipment Request", and "Password Reset". 

<p>
<img src="https://imgur.com/h4mxn5n.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/mw0396E.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
