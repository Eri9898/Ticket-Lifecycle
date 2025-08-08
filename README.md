# OSTicket Usaege Examples (Post-Install)
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>

</p>
<br />
This tutorial walks through how to create tickets as an end user, how to manage tickets as an Admin, and how Agents interact with tickets throughout the support lifecycle.
</p>
<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Creating Tickets as an End User</h2>
</p>
<br />
<img src="https://imgur.com/fsndTrp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
1. Go to the end user website http://localhost/osTicket/  and click on open a new ticket.
</p>
<br />
2. Enter the User's email and name to start creating a ticket.
</p>
<br />
3.Fill out the summary and the details and create the ticket
For this lab you can create multiple tickets with the different users/agents you created!
</p>
<br />
<h2>Assigning Tickets</h2>
</p>
<br />
<img src="https://imgur.com/69lGgqX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
1. You will log in as an Admin and look at the tickets, click on sign in as an agent.
<br />
</p>
<br />
<img src="https://imgur.com/rkypfaw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
2. Usually the Help Desk lead will assign the ticket to an Agent and also make sure the tickets follow SLA guidelines. So in order to do that you must click on a ticket and read through it. The top left corner lists the status of a ticket (opened, resolved or closed), the SLA, and Dept handling the ticket. Each of these can be edited by clicking on the word itself.
</p>
<br />
<h2>Set Ticket Priority</h2>
</p>
<br />
3. Click on priority to set it to high, low, or medium for the SLA
</p>
<br />
<h2>Assign to Agent</h2>
</p>
<br />
<img src="https://imgur.com/WRH1aFA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
4. Click next to "assigned to" and the list of Agents should open up. Then click on the name of the agent you want to send the ticket to.
</p>
<br />
<h2>Respond to User</h2>
</p>
<br />
5. Within the post reply tab you can respond to End User’s after updating their tickets. At the bottom you can select the ticket status. Then post the reply.
</p>
<br />
<h2>Leave Internal Notes</h2>
</p>
<br />
6. Next to the reply tab there is an internal notes tab used to relay notes if the ticket is being assigned or switched between multiple agents. 
</p>
<br />
<img src="https://imgur.com/IV7Q7kX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<h2>Ticket Status Lifecycle</h2>
</p>
<br />
7. When you back out onto the list of tickets, you should see the first one with updated priority and assignment.
If you select the open status it will remain in the queue. If you select resolved it will be grouped with closed tickets. 
If you click on a closed ticket you can review all the past edits made on the tickets and the responses between the end users and agents. It is a good habit to look at the history of closed tickets IRL to get an idea of what problems seem to happen the most as well as which solutions seem to work best.
</p>
<br />
8. You may repeat this process with multiple tickets and select different options for the status, priority, and SLA to see how it affects them.
</p>
<br />
<h2>Agent vs Admin Permissions</h2>
</p>
<br />

- Agents can:

   - View all tickets
     
   - Reply ONLY to tickets assigned to them
     
   - Leave internal notes
</p>
<br />

- Agents CANNOT:
  
   - Reassign or close tickets they don’t own
     
   - Edit SLA plans or roles
     
</p>
<br />

- Admins have full access:

    - Create/edit users, roles, SLAs, and departments
  
    - Assign & close tickets
  
    - Monitor all system activity
</p>
<br />
osTicket allows for streamlined help desk ticket tracking and management. With SLAs, department routing, role-based permissions, and easy-to-use interfaces for both end users and internal agents
 




