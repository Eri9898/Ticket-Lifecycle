# TicketLifecycleOSTicket
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket -Ticket Life Cycle</h1>
This tutorial outlines the Ticket lifecyle of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Creating Tickets as an End User</h2>

<p>

<img src="https://imgur.com/IsPsKoj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
1. Go to the end user website http://localhost/osTicket/  and click on open a new ticket.
</p>
<br />
2. Enter the End User's/ Client’s email and name to start creating a ticket.
</p>
<br />
3.Fill out the summary and the details and create the ticket
</p>
<br />
For this lab you can create multiple tickets with the different Client’s you created.!
</p>
<br />
<h2>Creating Tickets as an End User</h2>
</p>
<br />
</p>
<br />
<img src="https://imgur.com/LVNYJG2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
5. 
<br />
</p>
<br />
<img src="https://imgur.com/kY6gu50.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
6. 
Click create
</p>
<br />
7. Next you can create users (customers) for osTicket.
Click on the Agent Panel on the top right, then Users. Input their name and email "@osticket.com", then click Add New. 
</p>
<br />
</p>
<br />
<img src="https://imgur.com/WhaOpGP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
8. Now you will add your new SLA plans. Go to admin panel, then manage, then SLA.
	-Enter a name
-Select schedule, what days of the week
-Grace period, how soon it must be resolved.
-add plan
-Now you can go back to departments (see step 3 for how to get to departments if needed). Click on ea department and then from the SLA tab you can expand the list and choose from the SLAs you created. You do not need to select anything for schedule.


</p>
<br />
</p>
<br />
<img src="https://imgur.com/KGGPYvj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
9. Next you will configure help topics. This is a list that will pop up for end users when they want to select what general issue they have when creating their tickets. 
Click on Admin Panel, then manage then help topics.Click add new.
-Topic: Whatever issue you want to name ex. Computer issues or password reset
                       Status=active
                       Parent topic= top level 


