<p align="center">
<img src="https://i.imgur.com/Xhzke3A.png"
</p>

<h1>osTicket - Post-Installation Configuration</h1>
In the previous tutorial, we installed <a href="https://github.com/NicholasToon/osticket-prereqs"> osTicket. </a> In this tutorial, we will continue with the configuration process to familiarize you with its basic functions and setups.<br />

 <h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- PHP
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Departments
- Teams
- Allow anyone to create tickets
- Agents (Workers)
- Users (Customers)
- SLA (Service-Level Agreement)
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ideOqQG.png"/>
</p>
<p>
 
 <p>
<img src="https://i.imgur.com/hX3FO3D.png"/>
</p>
<p>
 
 <p>
<img src="https://i.imgur.com/62E0h6d.png"/>
</p>
<p>
 
 <p>
<img src="https://i.imgur.com/oJozv09.png"/>
</p>
<p>
 
<h3> Roles </h3>

Admin Panel -> Agents -> Roles -> Add New Role -> (Ex: Supreme Admin) -> Permisions -> Check All -> Tasks -> Check All -> Knowledge Base -> Check All -> Add Role (Supreme Admin will now appear in Roles)

(NOTE: To switch between the admin and agent panel look at the top of the page. If it reads Admin panel it means you are in the Agent panel. If it reads Agent panel then you are in the Admin panel.)

</p>
<br />

<p>
<img src="https://i.imgur.com/UPmyOMv.png"/>
</p>
<p>
 
 <p>
<img src="https://i.imgur.com/9Bh6r4a.png"/>
</p>
<p>
 
<h3> Departments </h3>
Admin Panel -> Agents -> Departments -> (Example) Name: System Administrators -> Create Dept (System Administrators will now appear in Departments 
</p>
<br />

<p>
<img src="https://i.imgur.com/mzBZR3C.png"/>
</p>
<p>

 <p>
<img src="https://i.imgur.com/r6tuQCl.png"/>
</p>
<p>
 
<h3> Teams </h3>

Admin Panel -> Teams -> Add New Team (If level I Support is not already created, then create it as you would Level II) -> Member -> Select Agent -> Add your created agent -> Create Team (Level II support will now have how ever many member(s) that were added to it)

</p>
<br />

<p>
<img src="https://i.imgur.com/ehfmvXL.png"/>
</p>
<p>
 
<h3> Allow Anyone to Create Tickets </h3>

Admin Panel -> Settings -> User -> Settings -> Registration Required: [√] Require registration and login to create tickets -> Save Changes

</p>
<br /><p>
<img src="https://i.imgur.com/MaxNrRg.png" />
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/yR5OO9T.png" />
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/bINkpDK.png" />
</p>
<p>
 
  </p>
<br /><p>
<img src="https://i.imgur.com/HepBntY.png" />
</p>
<p>
 
  </p>
<br /><p>
<img src="https://i.imgur.com/6Pqqjcl.png" />
</p>
<p>
 
 
<h3> Agents (Workers) </h3>
Admin Panel -> Agents -> Add New Agent -> Enter Credentials of your choice -> [√] Administrator -> Set Password -> [Uncheck] Send the agent a password reset email -> Set Password (I use Password1 for this tutorial) -> [Uncheck] Require password change at next login (Turn this off to save you headaches in the future) -> Access -> Primary Department -> System Administrators -> Select Role -> Supreme Admin -Extended Access -> System Administrators -> Permissions -> Select All -> Teams -> (Any one that you wish) Level II Support -> Create

Feel Free to create other Agents for the different departments, rolls,etc.


</p>
<br /><p>
<img src="https://i.imgur.com/GYkqc44.png"/>
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/gJ0YcAw.png"/>
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/xC77bbE.png"/>
</p>
<p>
 
  </p>
<br /><p>
<img src="https://i.imgur.com/adGTJys.png"/>
</p>
<p>
 
<h3> Users (Customers) </h3>

Agent Panel (You should see Admin Panel after you switch) -> Users -> Add User -> Enter Credentials -Add User (User will now appear in User Directory) -> Register -> [Uncheck] Send account activation email to [Customer Email] -> Set Password -> Create Account (User will now appear as active and registered)

Feel free to create other users.

</p>
<br /><p>
<img src="https://i.imgur.com/Pb3PMRU.png"/>
</p>
<p>

 </p>
<br /><p>
<img src="https://i.imgur.com/HXrYPiL.png"/>
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/uLhLnQS.png"/>
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/7JpaiWW.png"/>
</p>
<p>
 
 </p>
<br /><p>
<img src="https://i.imgur.com/E2mitYE.png"/>
</p>
<p>
 <h3> SLA (Service-Level Agreement) </h3>
 
 Admin Panel -> Manage -> SLA -> Add New SLA Plan -> Create Sev-A (It will now appear in Service Level Aggrements) -> Create Sev-B and Sev-C
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)
 
</p>
<br /><p>
<img src="https://i.imgur.com/WvOU9q6.png"/>
</p>
<p>
 
</p>
<br /><p>
<img src="https://i.imgur.com/s4YPIi5.png"/>
</p>
<p>
 
<h3> Help Topics </h3>

Admin Panel -> Manage -> Help Topics -> Add New Help Topic -> Create a handful of topics -> Add Topic

- Buisness Critical Outrage
- Personal Computer Issues 
- Equipment Request 
- Password Reset

Check your Help Topics dashboard and your new inputs will generated successfully.
 
Lorem ipsum dolor sit amet, 
