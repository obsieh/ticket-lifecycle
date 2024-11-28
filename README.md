<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
Step 1: Admin/Analyst and End-User Access


![image](https://github.com/user-attachments/assets/aa61100e-681f-474e-becc-2951e2df26d6)

</p>
<p>
Access the system via the Admin/Analyst Login Page at http://localhost/osTicket/scp/login.php for administrative tasks and ticket management. End users log in at http://localhost/osTicket to submit tickets and track their status. This step ensures clarity on roles and access points for managing support workflows.
</p>
<br />
Step 2: Department Adjustments


![image](https://github.com/user-attachments/assets/f19d98d0-515b-465c-b661-68c030bd73bb)

</p>
<p>
To maintain an organized structure, promote the SysAdmins Department to a Top-Level Department, enhancing visibility and control over its tickets. Additionally, delete the Maintenance Department to remove any unnecessary entries and simplify the department hierarchy.
</p>
<br />
Step 3: Ticket Management Scenarios

![image](https://github.com/user-attachments/assets/8721a5f7-48d7-45c8-b99a-781c745291e6)

</p>
<p>
End users create tickets describing specific issues, such as system outages or broken software. Help Desk Agents observe ticket properties like priority, SLA, department, and assigned agent. Agents then update these properties appropriately and resolve the tickets, working through realistic scenarios to practice handling and completing tickets efficiently.
</p>
<br />

Step 4: Escalations and Final Review

![image](https://github.com/user-attachments/assets/ed1a2a6f-9df5-4e5a-b1f3-898e0e784a39)

When tickets are escalated (e.g., set to Sev-A under SysAdmins), they may become inaccessible to certain agents. Admins must assign appropriate access rights in the Admin Panel. This process highlights how escalations and restricted permissions function within osTicket, ensuring proper workflows are maintained.
