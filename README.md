<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>


- <h2>Microsoft Azure (Virtual Machines/Compute)
 ![Screenshot 2024-05-25 162102](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/4a6602eb-08fb-4579-92db-9effa88e2c6e)

- <h2>Remote Desktop
![Screenshot 2024-05-25 183916](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/622e12c0-9911-41a8-ad28-1cce13e81d25)

- <h2>Internet Information Services (IIS) 
![Screenshot 2024-05-25 182940](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/d9dc366b-beaa-4cc7-9b97-f1ba9d7ec623)

<h2>Operating Systems Used </h2>

- <h2>Windows 10</b> (21H2)
 ![Screenshot 2024-05-25 183223](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/1e87bc76-a447-42d8-a23e-ec59f2766a5f)

<h2>Post-Install Configuration Objectives</h2>

        Configure Roles
          a.  Admin Panel -> Agents -> Roles
          b.  Supreme Admin
        Configure Departments
          a.  Admin Panel -> Agents -> Departments
          b.  System Administrators
        Configure Teams
          a.  Admin Panel -> Agents -> Teams
               i.   Level I Support
              ii.   Level II Support
        Allow anyone to create tickets
          a.  Admin Panel -> Settings -> User Settings
          b.  Registration Required: Require registration and login to create tickets 
        Configure Agents (workers)
          a.  Admin Panel -> Agents -> Add New
               i.   Jane
              ii.   John
        Configure Users (customers)
          a.  Agent Panel -> Users -> Add New
               i.   Karen
              ii.   Ken
        Configure SLA
          a.  Admin Panel -> Manage -> SLA
               i.   Sev-A (1 hour, 24/7)
              ii.   Sev-B (4 hours, 24/7)
             iii.   Sev-C (8 hours, business hours)
        Configure Help Topics
          a.  Admin Panel -> Manage -> Help Topics
               i.   Business Critical Outage
              ii.   Personal Computer Issues
             iii.   Equipment Request
              iv.   Password Reset



<h2>Configuration Steps</h2>

<p>


Login as User Admin. Notice on the top right there’s an Admin Panel button. Click on it to switch into the Admin Panel.


After switching to the Admin Panel, you’ll see the same button allows you to switch back to Agent Panel.


Stay on the Admin Panel and click on the Agents Tab.


Click on Roles.


Click on Add New Role.


Create a Supreme Admmin Role.


Click on the Permissions Tab.


Under Tickets, select all options.


Under Tasks, select all options.


Under Knowledgebase, select the option and finally click Add Role.


Click Departments.


Click on Add A New Department.


Fill in the name, select options and create the Department.


Click on Teams.


Click on Add Team.


Name the Team and create it.


Click on Members and add yourself to the team.


Under Settings, Users, Settings, uncheck Require Registration.


Click the Agents Tab and Add New Agent.


Create your first Agent.


Uncheck the boxes and set password.


Set Access Settings.


Click Create after selecting Team.


Go back to Agents and repeat steps for Agent 2.


Set Access Settings for Agent 2.


Create Users by going into the Agent Panel.


Click the Users Tab.


Create a new User.


Click User Directory and repeat steps for 2nd User.


Navigate to Admin Panel, Manage, and SLA.


Click on Add New SLA Plan.


Name and set rules for 1st SLA.


Create rules for 2nd SLA.


Create rules for 3rd SLA.


Configure Help Topics.


Create Business Critical Outage and repeat the steps for the others. All Helps Topics are listed on the final slide.


