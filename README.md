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

- Configure Roles (for grouping permissions)


- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/2eb0f2c3-a8d2-42ce-a5b5-cac383eccfb6)

Admin Panel -> Agents -> Roles
Supreme Admin

![image](https://github.com/user-attachments/assets/b016d879-066c-428d-bd58-5e1abaa92911)

Admin Panel -> Agents -> Departments
SysAdmins

![image](https://github.com/user-attachments/assets/ee8613ac-94a4-4324-85ea-1f30ec81c89a)

Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

![image](https://github.com/user-attachments/assets/1f506a89-2e85-4774-96e6-a020eed4447a)


Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

![image](https://github.com/user-attachments/assets/8c4e59d9-e330-45d6-8283-b1e7b393ebf5)

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

![image](https://github.com/user-attachments/assets/4bd27b59-1490-48d4-add0-90dea4aeb949)

Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

![image](https://github.com/user-attachments/assets/8be15c2d-a696-4446-8d57-7d15f0ace514)

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other




