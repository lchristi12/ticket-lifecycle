<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- OS Ticket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="1124" height="1302" alt="Screenshot 2025-09-01 040255" src="https://github.com/user-attachments/assets/ba098e5f-014e-4697-bf73-7def79449b95" />

</p>
<p>
As an end user, copy and paste this link http://localhost/osTicket, we are going to create a ticket under the user, Karen, that we created from the last tutorial. Click open ticket and fill out the contact information.

  For the help topic, select report a problem and in the issue summary, enter "entire mobile/online banking system is down". Give a description of the situation based on the issue summary and after click "create ticket". 
</p>
<br />

<p>
<img width="468" height="370" alt="Screenshot 2025-09-01 040521" src="https://github.com/user-attachments/assets/d1f02e93-da8c-47a7-8484-3390acd76b74" />
<img width="1278" height="484" alt="Screenshot 2025-09-01 040752" src="https://github.com/user-attachments/assets/caf7bbfc-2e2a-4686-b46e-6b574da9e4e5" />
<img width="1288" height="1304" alt="Screenshot 2025-09-01 041532" src="https://github.com/user-attachments/assets/1541d799-d5e5-47e5-83a5-6512df176879" />
<img width="1282" height="1346" alt="Screenshot 2025-09-01 042141" src="https://github.com/user-attachments/assets/87e007e9-44c5-434d-a740-55dfba818805" />

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties. As John, set SLA plan to Sev-A and give a description of the situation. Help topic, set as Business critical outage and provide a description/update of the situation. Since this is an online banking issue where the system is down, this is a Sev-A for the SLA. It is imperative to take care of an issue like this as soon as possible while keeping constant communication and updates.

  We have teams that we have set up. For situations specific tailored for online banking outage, as John, we can assign this ticket to the online banking teams so they can handle this issue. Provide description/updates.
</p>
<br />

<p>
<img width="504" height="374" alt="Screenshot 2025-09-01 042353" src="https://github.com/user-attachments/assets/139b94e8-b519-45ed-bc9e-97a8c3d4e3fb" />
<img width="1284" height="1318" alt="Screenshot 2025-09-01 042547" src="https://github.com/user-attachments/assets/68a68a01-d0dc-475c-b054-ccb7cddb8199" />
<img width="964" height="1242" alt="Screenshot 2025-09-01 043520" src="https://github.com/user-attachments/assets/ea5bc700-e90a-4ae0-ac4f-e4d5baf2f6ed" />

</p>
<p>
Next we are going to log in as jane, http://localhost/osTicket/scp/login.php, and work the ticket to completion. Jane is a under Supreme Admin and also member of the online banking team. There can be more than one person in the online banking team, you could assign it jane herself by clicking "Assigned To:" and select Jane. As Jane, provide update in the box saying she will take the ticket. While performing this part of the tutorial, try to simulate this like if this was an actual real life problem and provide updates as Jane (Admin/Online banking team) showing the situation is being taken care of and eventually completed. Observe in the pictures provided.

  This is only one example of how tickets are created and worked to completion. There can be many senarios like password reset or equipment issues that can explored in OS Ticket. Repeat this process by changing the sevarity of the ticket and showing interactions betweens jane (Admin), Karen (user), John (support), etc to get use to the different situations. As mentioned before, treat this as real life situations because it is important especially breaking into a help desk role.

  
