<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Ticket Lifecycle</h1>
This project will outline the lifecycle of tickets from creating to closing using this open-source (osTicket) ticketing system. This project is a continuation of the previous osTicket project that you can find here: https://github.com/brandenoz/post-install-config. 

<h2>Configuration Steps</h2>

<h3>Step 1: Create a Ticket</h3>

From this URL: http://localhost/osTicket/ click Open a New Ticket. 
- For the email and name put karen@lognpacific.com and karen for the user we created in our previous project. 
- Help Topic: Report a Problem. Issue Summary: entire mobile/online banking system is down. Issue Description: My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it, cannot log in. Click Create Ticket. <br>
<br>

![1](https://github.com/user-attachments/assets/332fc0c5-8680-4bc1-bf67-e36eb998ea07)

<h3>Step 2: Login as John</h3>

Log out of the admin account and log into the non-admin account, as John. 
- If you followed the previous project, the credentials should be john for the username and Password1 for the password. 
- Delete the osTicket Installed! Ticket if you would like. 
- Open the ticket that we just created. <br>

![2](https://github.com/user-attachments/assets/2d235d9c-55d2-4930-b171-d18164939f78)

- Set hte SLA to Sev-A as this issue would be a top priority. For the description put “Wide impact, customers unable to do online banking” and click Update. 
Change the Help Topic to Report a Problem / Business Critical Outage. For the description type: “No customers able to access online banking” click Update. <be>

![3](https://github.com/user-attachments/assets/432e94ef-648e-4ff3-8fe6-b0f46209ceb2)

- Refresh the page and observe that the ticket thread now has marked our changing of the ticket status. 
- Change the Assigned To: to the Online Banking Team, for the description, “Customers not able to access online banking portal, assigning to online banking team.” click Assign. 
- Step 3: Login as Jane
- Logout from John and log in as Jane, open our ticket. 
- Reassaing the ticket from the Online Banking team to Jane Doe, in the description type: “I'll be taking this ticket.” Click Assign. 
- Post a reply: “I suspect the problem might be related to the recent updates. We tested them sufficiently, but I'm going to look into it further and roll it back if I ﻿determine that was the cause.” Click Post Reply. 
- Post another reply: “It was determined the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running.” Click Post Reply. 
 -Change the ticket status at the top to “Resolved”. This will effectively close the ticket successfully. <br>

![4](https://github.com/user-attachments/assets/1171382b-d452-442f-ac65-ebf4678f9955)

<h3>Step 4: Create a New Ticket</h3>

From this URL: http://localhost/osTicket/ click Open a New Ticket. 
- For the email and name put karen@lognpacific.com and karen for the user we created in our previous project. 
- Help Topic: Report a Problem. Issue Summary: accounting department needs adobe upgrade, broken. Issue Description: It looks like many people in the accounting department can't use their adobe software. Click Create Ticket. 


<h3>Step 5: Login as John, again</h3>

Login as John. Open the new ticket. 
- Change the SLA to Sev-C, adding a note: “Only 2 people unable to open Adobe reader, classifying as Sev-C.” Click Update. 
- Assign to John Doe, click Assign. 
- Post Reply: “Cx states only 2 people in the accounting department unable to open and use Adobe reader. Cx testing restart, will call back after lunch.” Post Reply. 
- Post Reply: “Cx states that restart fixed issue, closing out ticket.” Set ticket status to Resolved. Post Reply. This ticket will now be closed. 
- Step 6: Create a New Ticket
- From this URL: http://localhost/osTicket/ click Open a New Ticket. 
- For the email and name put karen@lognpacific.com and karen for the user we created in our previous project. 
- Help Topic: Report a Problem / Personal Computer Issues. Issue Summary: CFO states he is unable to use a laptop. Issue Description: Laptop won’t power on, despite pressing the power button. Click Create Ticket.

<h3>Step 7: Open New Ticket</h3>

As John, open and begin editing the ticket. 
- Change the SLA Plan to Sev-B with a note “May re-classify after getting more info.” Update. 
- Reassign the ticket to John. 
- Post Reply: “CFO’s laptop was not charging due to broken charger, bought new charger, not successfully charging.” Change the status to Resolved. Post Reply. 

<h3>Step 8: Other Features</h3>

There are many other features that can be explored depending on your curiosity and or business needs such as: 
- Checking a ticket status, or having the ticket status emailed to yourself. 
- If you change the Priority, such as to Emergency, then you go to the My Tickets view, you will see the ticket is colored red for Emergency. <br>

![5](https://github.com/user-attachments/assets/daf6debf-e1ac-490a-8548-7255686fdf04)

<h3>Step 9: Cleaning Up</h3>

As with previous projects, if you are done with this project permanently, delete the resource group. Wait until notification of successful deletion appears to consider the task done. 
- If you plan to pause and come back, I recommend stopping the VM and waiting for successful notification before walking away. 
- To try a different project with this VM, see other project here: https://github.com/brandenoz. 
