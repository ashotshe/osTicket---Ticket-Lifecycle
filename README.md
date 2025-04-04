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
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
These are the different stages of a ticket through its creation to resolution

- Intake: The ticket is created by the user or an agent. 
- Assignment and Communication: The ticket is assigned to a department or agent, with communication with the user.
- Working the Issue: The agent works on resolving the issue and/or provides necessary updates.
- Resolution: The ticket is resolved and closed after verification with the user. 

Prioritizing Tickets Through SLAs (Service Level Agreements)

-SLAs are the crucial piece that ensures that tickets are resolved within specific timeframes, dependent
upon the issue's severity. Below are the different severity levels, each aligning with its specific SLA to prioritize and
resolve tickets efficiently and effectively: 

-Sev-A (1 hour, 24/7): The hightest priority for critical issues, and in this case, the toll system network
was down. This SLA requires a resolution within 1 hour, and this ticket was escalated up to the SysAdmins
team for 24/7 resolution. 
-Sev-B (4 hours, 24/7): Important, yet less urgent issues, for in this case, the CLM (Cash Logistics Manager) was not 
working properly, due to a network error. This SLA ensures a 4-hour response and resolve, yet is still available for 
24 hours. 
-Sev-C (8 hours, business day): The lower priority issues are under this level, such as resetting the password in the 
video. 

-Adhering to these SLAs ensures that the more severe issues in osTicket are prioritized immediately, while
making sure tha the lower level issues are handled effectively. 

-Triaging Tickets

We demonstrated how the tickets are evaluated either solve the problem, or to escalate to a higher level 
of support. Triaging is the element needed to make that things are moving efficiently and in a timely manner. 

Solving Problems and Closing Tickets

Please see the following step by step example:

<h1>Resolving Tickets in osTicket</h1>
In this lab I go through the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<p>
<img src="https://i.imgur.com/kTlhwFo.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/RlHNrkW.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/ApsciFm.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p>
In order to create tickets, users have to enter the ticket portal and log in if necessary. Within the portal, the user can submit a ticket request and detail their IT related issues. Here, I have created three tickets detailing a variety of problems that can appear as tickets in a real environment. Tickets are created by using a Help Topic, a descriptive outline of the issue, and the details of the issue that are all written as if it were an email.
</p>
<br />

<p>
<img src="https://i.imgur.com/8J4gYRr.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/COfD3VN.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p>
From the perspective of an admin, they will receive the ticket requests from their panel once they are sent. The admins can then reassign tickets to an agent or appropriate team. The severity level of the issue is determined and assigned accordingly to make sure appropriate tickets are solved within an SLA. Here, Jane viewed this ticket and assigned it to the System Administrators and changed the severity level to Emergency. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Y1OaeVl.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/pU3kh02.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/YhXK7WL.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p>
When resolving tickets, it is important to have strong communication. One has to communicate with their team and the affected users. Tickets come and go with different issues and are assigned appropriately to different people. One of these tickets are assigned to John from Jane and Jane herself was able to manage a ticket by herself. Documentation is crucial to a successful environment. Tickets need to be documented properly so they can be used as reference if a similar issue shows up in the future.
</p>
<br />

<h2>Lessons Learned</h2>

The protocols for how tickets are managed can differ depending on the work environment. There may be a quota for how many tickets need to be resolved within a certain time frame and certain tickets will have to be prioritized depending on the situation. I have built osTicket from scratch and was able to understand how tickets work in an IT position.
