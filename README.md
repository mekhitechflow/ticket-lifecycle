<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- 

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

<p>
<img width="830" alt="Screenshot 2024-09-01 at 7 29 55 PM" src="https://github.com/user-attachments/assets/e9d8d5e3-92fe-423d-8c8b-98edd7677807">
</p>
<p>
This is the ticket portal for users, this is where they are able to create tickets and in osTicket we will be able to see them once they are sent through the system. Go to this link --> http://localhost/osTicket/index.php to access this portal for our users we created so we can start creating tickets to resolve.
</p>
<br />

<p>
<img width="828" alt="Screenshot 2024-09-01 at 7 32 25 PM" src="https://github.com/user-attachments/assets/9f0c3e17-2150-489c-8967-782559ca99df">
</p>

<br />

<p>
<img width="826" alt="Screenshot 2024-09-01 at 7 33 50 PM" src="https://github.com/user-attachments/assets/f56d0818-2c89-4f0b-abcd-a3557d25e0e7">
</p>

<br />

<p>
<img width="821" alt="Screenshot 2024-09-01 at 7 36 12 PM" src="https://github.com/user-attachments/assets/c96b7375-1960-43fb-b07a-55560ec3c1cb">
</p>

<p>
Here I've created 3 different tickets, all of them having different levels of importance, so that I am able to have real-world practice escalating certain tickets to higher members and taking care of the ones I am capable of doing. Furthermore, in this section, they are able to present the problem and choose themselves what topic this falls under, if you take a look at each image they all vary in urgency. It's just like submitting an email but instead, you're reaching out for assistance!
</p>
<br />

<p>
<img width="951" alt="Screenshot 2024-09-01 at 7 44 44 PM" src="https://github.com/user-attachments/assets/31b13681-a6c3-4ea8-9091-00643a4c86ea">
</p>
<p>
Now that the tickets are created, we need to go back to our portal so that we can assist the users, use the link --> http://localhost/osTicket/scp/login.php to access your login and proceed from there! Furthermore, this is the home page for all agents, it shows all the tickets that were created and from here you are able to resolve them.
</p>
<br />

<p>
<img width="946" alt="Screenshot 2024-09-01 at 8 17 15 PM" src="https://github.com/user-attachments/assets/ad742080-d76e-4a48-aeef-a47f9aaaefd5">
</p>
<p>
I am going to key in on the "Business Critical Outage" example we went with. So as you can see in the image above, I previously logged in using my other agent (Jane Adams), hypothetically speaking she changed the priority to Emergency & sent this to System Administrators which is a department that is more equipped to handle this specific situation. After, I logged back into my admin account because this account is the only one that can assess this issue!
</p>
<br />

<p>
<img width="945" alt="Screenshot 2024-09-01 at 8 28 16 PM" src="https://github.com/user-attachments/assets/1c11066e-4ef3-4877-b89d-64a5e916509a">
</p>
<p>
Once on the ticket! I went ahead and put a note and assigned SEV-A SLA to the ticket to get my team to understand the importance of this ticket so that we can get this one fixed and resolved. You simply do this by clicking SLA in the top part of the ticket and assigning whichever one you think fits the situation for this one its SEV-A.
</p>
<br />

<p>
<img width="957" alt="Screenshot 2024-09-01 at 8 36 25 PM" src="https://github.com/user-attachments/assets/d601b8c3-3db2-4f5b-8e28-581269b04970">
</p>
<p>
Hypothetical scenario, communicating that my team figured out the issue and closing/resolving the ticket!
</p>
<br />

<p>
<img width="950" alt="Screenshot 2024-09-01 at 7 53 20 PM" src="https://github.com/user-attachments/assets/e2c1ccf5-e77a-4d0b-94a4-943ad246a8c7">
</p>
<p>
This shows the dashboard with all the tickets closed/resolved, in this section, we only covered the most complicated ticket that was sent in. The same steps were taken for the other tickets but instead of assigning the ticket to a higher department, I simply logged in with my other agents and took care of the tickets from their point of view.
</p>
<br />
