<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Departments
- Creating Tickets
- Teams
- SLA Managment

<h2>Configuration Steps as a Admin & Agent</h2>

<p>
<img src="https://imgur.com/2WBAkxS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you're logged into your osTicketing System, in your top right corner, you want to click on admin. Next click the agents tab, roles & [Add new role]. Name it [Supreme Admin]. Go to next to [permissions] this is where you can add them. Check all the ones under Tickets & task. Then click add role to confirm.
</p>
<br />

<p>
<img src="https://i.imgur.com/6xDTkPd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lets create a department. Be in the admin panel Go to agents tab & departments. Click add new deparment. Call it [System Admin] then create it.
</p>
<br />

<p>
<img src="https://imgur.com/OiR1cKS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we're going to make some teams. Be in admin panel. Go to agents then teams. Click Add new teams & add "Level II Support". Go to the members tab and add yourself to that team.
</p>
<br />

<p>
<img src="https://imgur.com/hWhKy1y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we're going to create agents. Make sure in the admin panel, agents & Add new. Add Jan doe & John Doe. Make up a fake email, make user name [jane.doe]. Hit set password, uncheck [Send agent password reset through email]. Set password how you want it. Then click set. Go to access tab and select system admin & make her a supreme admin. Go to team and add them to level II support. Then click create. Add one more John Doe.
</p>
<br />

<p>
<img src="https://imgur.com/fOecFgH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we're going to configure users. Go to Agent panel & add new user. Karen [or whoever]. Create email & Name.  
</p>
<br />

<p>
<img src="https://imgur.com/youZrqV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now configure a SLA. Go back to Admin panel, Manage & SLA. Create 1.) Sev-A (1hr, 24/7) 2.) Sev-B (4hrs, 24/7) & Sev-C (8hrs, Business hrs) 
</p>
<br />

<p>
<img src="https://imgur.com/LRlxu9n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now configure Help Topics. 1.) Business Critical Outage. 2.) Personal Computer Issues. 3.)Equipment Request 4.) Password Reset.
</p>
<br />
 
