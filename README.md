<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Example tickets and solutionsh1
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img width="473" alt="image" src="https://github.com/user-attachments/assets/577eb7ed-628a-403c-ab42-6e4c42b2984b">
</p>

<p>
1.As an end-user, create the following ticket: entire mobile/online banking system is down
</p>
<p>
<img width="475" alt="image" src="https://github.com/user-attachments/assets/ba9614b3-fe28-4698-a248-395c20de0fc4">
</p>
<p>
 2.As Help Desk Agent (john), observe the ticket’s properties, Priority, Department, SLA,Assigned To
</p>

<p>3. Set Up Roles (Group Permissions)
Navigate to Admin Panel > Agents > Roles.
Create and assign Roles to group permissions. Example: Supreme Admin for full access.</p>
<br />

<p>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/c1ad7a0f-15f5-41fc-a9d7-5530dc0f173e">

</p>
<p>
4. Define Departments (Ticket Visibility)
Go to Admin Panel > Agents > Departments.
Create departments to organize ticket visibility based on job and level of access allowed, for example: helpdesk, system admin, accounting
</p>
<p>5. Configure Teams
Go to Admin Panel > Agents > Teams.
Create Teams to pull agents from various departments to work on specific issues. Example: Online Banking team.</p>
<p>6. Allow Ticket Creation Options for Users
Go to Admin Panel > Settings > User Settings.
Uncheck "Registration Required" if you want anyone to be able to create tickets without an account.
Check "Require registration" if only registered and logged-in users should be allowed to create tickets.</p>
<p>7. Add Agents (Workers)
Go to Admin Panel > Agents > Add New.
Add agents, specifying their departments:
Jane - Department: SysAdmins,
John - Department: Support</p>

<p>8. Add Users (Customers)
Go to Agent Panel > Users > Add New.
Add customer profiles for users who will be submitting tickets: Karen, Ken</p>
<br />

<p>
9. Configure SLA (Service Level Agreements)
Go to Admin Panel > Manage > SLA.
Set SLA rules for different priority levels:
Sev-A: Grace Period - 1 hour, Schedule - 24/7,
Sev-B: Grace Period - 4 hours, Schedule - 24/7,
Sev-C: Grace Period - 8 hours, Business Hours only
</p>
<p>10. Define Help Topics (Ticket Categories)
Go to Admin Panel > Manage > Help Topics.
Create Help Topics to guide users when submitting tickets:
Business Critical Outage,
Personal Computer Issues,
Equipment Request,
Password Reset
Other</p>
<br />
