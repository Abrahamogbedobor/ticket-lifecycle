.<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This project outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- osTicket End-Users
- osTicket Professional
- Using osTicketing Platform
- Resolution and Working out Issues

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/r9dTgXL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/7YveGfI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Essentially, this stage involves creating new ticket for help desk professional to resolved using the URL of osTicket end-users. The above figures shows the steps or stages that were used by end users to create a new ticket. Also, users could provide brief summary of the ticket they are reporting on the 'issue summary' section of the form as well as giving further details on reasons why the ticket is been raised.
</p>
<br />

<p>
<img src="https://i.imgur.com/HMg1eOZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/BfcW0Me.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/3YW1QPb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/FBYTTv9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figures shows osTicket professionals logging into osTicket platform, in order to troubleshoot and resolved raised tickets from end-users. Notably, the first agent Jane Doe was unable to view or amend raised tickets from  end-users after she logged-in as an agent whereas the second user (admin) as shown above was able to view and amend tickets. This is because, permission was not granted to Jane Doe during osTicket configuration stage.
</p>
<br />

<p>
<img src="https://i.imgur.com/YhiGJrt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TdPhlhO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/teCvHST.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figures describes the steps used by osTicket admin to grant permision to Jane Doe. Notably, the users with administrative privilege was referred to as admin on this lab. In granting permission to Jane Doe, firstly, someone with admin access logged into osTicket admin page, then agent tab was clicked to displayed the above agents page. Secondly, the agent that needed permission such as Jane Doe was then clicked. Finally, access tab was entered to grant the necessary permission to Jane Doe as shown above.
</p>
<br />

<p>
<img src="https://i.imgur.com/dHgE7X8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figure shows Jane Doe logging back to osTicketing platform after been granted supreme admin access, this then enabled her to view, troubleshoot and amend tickets that are raised by end-users.
</p>
<br />

<p>
<img src="https://i.imgur.com/ms8UKdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane Doe has successfully logged into osTicket platform with access to all raised tickets. Notably, the appeared tickets has not yet been prioritise in regards to their SLA importance. Also, at the right end, tickets will be assigned by queue manager to an agent after been prioritise according to their importance to the organisation.
</p>
<br />

<p>
<img src="https://i.imgur.com/yN5Xi9S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/pdJDghU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XmTVea1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/91n8KZE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figures shows osTicket that was raised by an end-user. An agent named Jane Doe opened the ticket to check its content. The ticket says an entire online mobile banking is down, assuming Jane is the queue manager or escalation engineer resposnible for setting ticket priority, assigning tickets to agents, as well as setting up SLA plan. She then set-up tickets priority from "Normal to either low, high or emergency" with some note beneath. Also, tickets was assigned to particular agents, and SLA plan was set to SEV A, B or C as shown above.
</p>
<br />

<p>
<img src="https://i.imgur.com/a9zeHLY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Notably, in some scenario customers would be able to set-up tickets SLA when raising tickets. In that case, queue manager could either downgrade its severity from A to B or C depending on its impact to the organisation. Furthermore, each time a ticket is amended or assigned to an agent there would be a ticket threads or histroy as shown above highlighting the various changes and time that a particular ticket is been amended.
</p>
<br />

<p>
<img src="https://i.imgur.com/8Px5skE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figure shows the new interface of raised tickets by end users after been amended by queue manager.
</p>
<br />

<p>
<img src="https://i.imgur.com/YYnhP4q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/WdKSGg5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ticket was assigned by queue manager to an agent, and such ticket has been resolved by Jerry who is a syst engineer with a short note added for admin team to be aware that a particular ticket has been resolved and also, the named agent who resolved it before posting the ticket. Note from the second figure that the resolved tciket has disappered from the list because it statue was changed from open to resolved. However, a new team memeber could re-visit all closed ticket if necessary as this is a good practice of becoming a better 'help desk professional' as one could have the opportunity of learning the techniques used by senior colleagues in resolving tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hXxGFVZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figure shows the interface of closed ticket in osTicketing platform. This allows new employees to have a refresher on the approach used by previous employees to troubleshoo and amend raised tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/8Px5skE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Learn what osTicket was, virtual machine in Asure, install all pre-requisite, install osTicket itself, configure it with SLA and users, created a few tickets with different severity and SLA levels, used various helpdesk profession to log in and solved ticketing issues.
</p>
<br />
