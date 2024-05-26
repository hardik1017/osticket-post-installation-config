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
 
![Screenshot 2024-05-25 190507](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/c5cb80e8-7eee-4410-9912-ee565206d505)

<p>

Login as User Admin. Notice on the top right there’s an Admin Panel button. Click on it to switch into the Admin Panel.

<p>

![Screenshot 2024-05-25 190631](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/475a85f8-5929-4758-a3ea-90b57e073aae)

<p>
 
After switching to the Admin Panel, you’ll see the same button allows you to switch back to Agent Panel.

<p>

![Screenshot 2024-05-25 191917](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/98e6d65b-7c85-4d88-bc14-ff745beaa655)

<p>

Stay on the Admin Panel and click on the Agents Tab.


<p>

![Screenshot 2024-05-25 193131](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/bbd5c4a2-cb86-420b-9c2e-7fd9e21103b0)


Click on Roles.

<p>


![Screenshot 2024-05-25 193803](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/f127f869-19ce-434e-bdc3-895bb5f1d10e)


Click on Add New Role.

<p>


![Screenshot 2024-05-25 193908](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/04748fc0-612c-4eb4-b159-619f02a3c3b3)


Create a Supreme Admmin Role.

<p>

![Screenshot 2024-05-25 194001](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/fbc7d5de-c651-4be6-ab67-2fc9dc8e1445)



Click on the Permissions Tab.

<p>
 
![Screenshot 2024-05-25 194654](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/08d8b82c-f818-43de-a1f3-51af4316f2bc)



Under Tickets, select all options.

<p>


![Screenshot 2024-05-25 194750](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/05636e8d-9d8f-43d5-9ba1-2df53815a53e)


Under Tasks, select all options.

<p>


![Screenshot 2024-05-25 195337](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/97028602-50c3-491c-9bfe-334a4f4c3b2c)


Under Knowledgebase, select the option and finally click Add Role.

<p>

![Screenshot 2024-05-25 195434](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/5e0c31c9-6efb-4646-8196-bd590ece206b)



Click Departments.

<p>

![Screenshot 2024-05-25 195511](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/72319029-be35-4c40-a636-301b3d9410c7)


Click on Add A New Department.

<p>

![Screenshot 2024-05-25 195553](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/c633f71c-c87c-4188-bda8-8590a69e6b2c)



Fill in the name, select options and create the Department.

<p>

![Screenshot 2024-05-25 210559](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/c9469a75-de4d-41eb-94a3-e3574c7ceb6c)



Click on Teams.

<p>

![Screenshot 2024-05-25 210652](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/ad74753f-69dd-45ec-836d-79eaff46e905)


Click on Add Team.

<p>

![Screenshot 2024-05-25 210752](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/728615cd-1434-4b6b-9d32-40b17c679fa2)



Name the Team and create it.

<p>

![Screenshot 2024-05-25 210830](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/c49516bb-cecf-40ab-bd94-66e739124357)



Click on Members and add yourself to the team.

<p>

![Screenshot 2024-05-25 210933](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/b3d52f77-dce2-48cf-b6c2-fa0b0414cb75)



Under Settings, Users, Settings, uncheck Require Registration.


<p>

![Screenshot 2024-05-25 211122](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/bcfd4115-badf-4af4-bd21-a6cefaa58dc8)



Click the Agents Tab and Add New Agent.


<p>

![Screenshot 2024-05-25 211241](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/c1ab5567-0d08-4e48-aa7c-56d75fc09dca)




Create your first Agent.


<p>

![Screenshot 2024-05-25 211513](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/39d2d111-6c20-4f57-82dd-5424bd19ecf8)


Uncheck the boxes and set password.

<p>

![Screenshot 2024-05-25 211555](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/6dbe191d-5f98-4a8b-8e02-20d95b9b0bfb)


Set Access Settings.

<p>

![Screenshot 2024-05-25 211750](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/83cb4ac2-ce85-417f-b947-c246a1526c47)

Click Create after selecting Team.

<p>

![Screenshot 2024-05-25 211914](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/04e3a2df-a0de-4f6e-816c-d4eb882368d1)


Go back to Agents and repeat steps for Agent 2.

<p>
 
![Screenshot 2024-05-25 212010](https://github.com/hardik1017/osticket-post-installation-config/assets/170269652/6699e967-d5e7-4863-96b4-0093d1d1f6f0)


Set Access Settings for Agent 2.

<p>


Create Users by going into the Agent Panel.

<p>


Click the Users Tab.

<p>


Create a new User.

<p>


Click User Directory and repeat steps for 2nd User.

<p>


Navigate to Admin Panel, Manage, and SLA.


<p>

Click on Add New SLA Plan.

<p>


Name and set rules for 1st SLA.


<p>

Create rules for 2nd SLA.

<p>


Create rules for 3rd SLA.

<p>


Configure Help Topics.


Create Business Critical Outage and repeat the steps for the others. All Helps Topics are listed on the final slide.


