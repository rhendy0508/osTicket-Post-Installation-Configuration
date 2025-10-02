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

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (Grouping Permissions)
- Configure Departments (Ticket Visibility)
- Configure Teams (Cross-Department Collaboration)
- Configure User Registration Settings
- Configure Agents (Help Desk Staff)
- Configure Users (End-Users / Customers)
- Configure SLA Policies
- Configure Help Topics (Ticket Categorization)

<h2>Configuration Steps</h2>

<p>
<img src="/images/step1-post-config.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Configure Roles (for grouping permissions) → Navigate to Admin Panel → Agents → Roles → Create role: Supreme Admin.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Configure Departments (Ticket Visibility) → Navigate to Admin Panel → Agents → Departments → Create department: SysAdmins.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Configure Teams → Navigate to Admin Panel → Agents → Teams → Create team: Online Banking → Pull agents from different departments as needed.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Configure User Registration Settings (Ticket Access Control) → Navigate to Admin Panel → Settings → User Settings → Uncheck "Unregistered users can create tickets" → Require registration/login to create tickets.


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Configure Agents (workers) → Navigate to Admin Panel → Agents → Add New → Example: Jane (Dept: SysAdmins), John (Dept: Support).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Configure Users (customers) → Navigate to Agent Panel → Users → Add New → Example: James and Janis.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7: Configure SLA → Navigate to Admin Panel → Manage → SLA → Create policies: Sev-A (1 hr, 24/7), Sev-B (4 hrs, 24/7), Sev-C (8 hrs, Business Hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: Configure Help Topics (For when users create a ticket) → Navigate to Admin Panel → Manage → Help Topics → Add: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other.
</p>
<br />
