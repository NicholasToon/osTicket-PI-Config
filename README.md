![Image](https://i.imgur.com/Xhzke3A.png)

# osTicket - Post-Installation Configuration
In the previous tutorial, we installed <a href="https://github.com/NicholasToon/osticket-prereqs"> osTicket. </a> In this tutorial, we will continue with the configuration process to familiarize you with its basic functions and setups.

 ## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- PHP
- osTicket

## Operating Systems Used 

- Windows 10 (21H2)

## Post-Install Configuration Objectives

- Roles
- Departments
- Teams
- Allow anyone to create tickets
- Agents (Workers)
- Users (Customers)
- SLA (Service-Level Agreement)
- Help Topics

## Configuration Steps

![Image](https://i.imgur.com/5fCE6jK.png)
 
![Image](https://i.imgur.com/hX3FO3D.png)
 
![Image](https://i.imgur.com/62E0h6d.png")
 
![Image](https://i.imgur.com/oJozv09.png)
 
### Roles

**Admin Panel** -> **Agents** -> **Roles** -> Add New Role -> (Example: Supreme Admin) -> **Permissions** -> Check All -> **Tasks** -> Check All -> **Knowledge Base** -> Check All -> **Add Role** (Supreme Admin will now appear in Roles).

(NOTE: To switch between the admin and agent panels, look at the top of the page. If it reads "Admin panel," it means you are in the Agent panel. If it reads "Agent panel," then you are in the Admin panel.)

![Image](https://i.imgur.com/UPmyOMv.png)
 
![Image](https://i.imgur.com/9Bh6r4a.png)
 
### Departments 
Admin Panel -> Agents -> Departments -> (Example) Name: System Administrators -> Create Dept (System Administrators will now appear in Departments) 


![Image](https://i.imgur.com/mzBZR3C.png)

![Image](https://i.imgur.com/r6tuQCl.png)
 
### Teams 

Admin Panel -> Agents -> Teams -> Add New Team (If level I Support is not already created, then create it as you would Level II) -> Member -> Select Agent -> Add your created agent -> Create Team (Level II support will now have how ever many member(s) that were added to it)

![Image](https://i.imgur.com/ehfmvXL.png)
 
### Allow Anyone to Create Tickets

Admin Panel -> Settings -> Users -> Settings -> Registration Required: [√] Require registration and login to create tickets -> Save Changes

![Image](https://i.imgur.com/MaxNrRg.png)
 
![Image](https://i.imgur.com/yR5OO9T.png)
 
![Image](https://i.imgur.com/bINkpDK.png)
 
![Image](https://i.imgur.com/HepBntY.png)
 
![Image](https://i.imgur.com/6Pqqjcl.png)
 
 
### Agents (Workers) 
Admin Panel -> Agents -> Add New Agent -> Enter Credentials of your choice -> [√] Administrator -> Set Password -> [Uncheck] Send the agent a password reset email -> Set Password (I use Password1 for this tutorial) -> [Uncheck] Require password change at next login (Turn this off to save you headaches in the future) -> Access -> Primary Department -> System Administrators -> Select Role -> Supreme Admin -Extended Access -> System Administrators -> Permissions -> Select All -> Teams -> (Any one that you wish) Level II Support -> Create

Feel Free to create other Agents for the different departments, rolls,etc.


![Image](https://i.imgur.com/GYkqc44.png)
 
![Image](https://i.imgur.com/gJ0YcAw.png)
 
![Image](https://i.imgur.com/xC77bbE.png)
 
![Image](https://i.imgur.com/adGTJys.png)
 
### Users (Customers)

Agent Panel (You should see Admin Panel after you switch) -> Users -> Add User -> Enter Credentials -Add User (User will now appear in User Directory) -> Register -> [Uncheck] Send account activation email to [Customer Email] -> Set Password -> Create Account (User will now appear as active and registered)

Feel free to create other users.

![Image](https://i.imgur.com/Pb3PMRU.png)

![Image](https://i.imgur.com/HXrYPiL.png)
 
![Image](https://i.imgur.com/uLhLnQS.png)
 
![Image](https://i.imgur.com/7JpaiWW.png)
 
![Image](https://i.imgur.com/E2mitYE.png)
 
 ### SLA (Service-Level Agreement)
 
 Admin Panel -> Manage -> SLA -> Add New SLA Plan -> Create Sev-A (It will now appear in Service Level Aggrements) -> Create Sev-B and Sev-C
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)
 
![Image](src="https://i.imgur.com/WvOU9q6.png)
 
![Image](https://i.imgur.com/s4YPIi5.png)
 
### Help Topics

Admin Panel -> Manage -> Help Topics -> Add New Help Topic -> Create a handful of topics -> Add Topic

- Buisness Critical Outrage
- Personal Computer Issues 
- Equipment Request 
- Password Reset

Check your Help Topics dashboard and your new inputs will have generated successfully.
 
## Congratulations! You have successfully set up the core configurations of osTicket. If you would like to explore further ticket manipulation, you can find a Example that I have prepared for you to emulate and expand upon by clicking [here](https://github.com/NicholasToon/osTicket-Ticket-Lifetime-Example). 
 
Thank you for reading!
