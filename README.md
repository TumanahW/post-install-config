<p align="center">
  
![Screenshot 2024-12-04 at 1 44 07 PM](https://github.com/user-attachments/assets/e41d150e-ee89-4a4b-ac04-eb60fb9d5093)
  
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [Post Installation Configuration osTicket](https://www.loom.com/share/68fe3690530a4d6a8fc80ca563d938ff)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
<ol>
<li>Configure User Roles and Permissions
-Set up user roles to define access levels and permissions. </li>
<li> Customize Ticket Queues and Workflows
-Design and implement ticket queues tailored to organizational needs</li>
<li>Implement SLA (Service Level Agreement) Policies
-Create and apply SLA rules to enforce response and resolution timeframes, ensuring adherence to support standards and client expectations.</li>
<li>Develop Custom Help Topics and Forms
-Set up help topics and custom forms to guide users in ticket submissions, providing structured input for better issue categorization and troubleshooting.</li> 
</ol>

<h2>Configuration Steps</h2>
<p> For this guide,osTicket needs to have an established connection  using HeidiSQL. This is a continuation of the previous installation guide.<p/>
<p>
  
![Screenshot 2024-12-04 at 3 49 00 PM](https://github.com/user-attachments/assets/d7185279-7dee-47e6-8185-035da3f30fef)
</p>
<br />

![Screenshot 2024-12-04 at 4 02 18 PM](https://github.com/user-attachments/assets/517c0bc6-be76-4dcf-b6da-4d7a6dc7213a)
<br/> 
<p> we created a username and password at the end of the tutorial  when we installed HeidiSQL. Now is the time to input that username and password to create the connection.</p>

![Screenshot 2024-12-04 at 4 04 35 PM](https://github.com/user-attachments/assets/4fb87963-eefb-475e-88d3-b1bfcf9eac0a)

![Screenshot 2024-12-04 at 4 05 06 PM](https://github.com/user-attachments/assets/1bf39028-8ece-41c5-a14f-3b58334b2d57)
![Screenshot 2024-12-04 at 4 05 30 PM](https://github.com/user-attachments/assets/1a3076e9-c2f2-4495-a138-e2faf1240a3d)
![Screenshot 2024-12-04 at 4 06 08 PM](https://github.com/user-attachments/assets/563d33ca-4dfa-4f3f-8adb-378eaa4b4d99)
![Screenshot 2024-12-04 at 4 06 34 PM](https://github.com/user-attachments/assets/c6670ebc-8ca7-45aa-83a4-e72632a7a50f)
![Screenshot 2024-12-04 at 4 08 33 PM](https://github.com/user-attachments/assets/a87bdd73-c5a1-4f20-9f91-c8ab57a9589d)

<p> With the osTicket database created , we will input login information into the databse setting.</p>

![Screenshot 2024-12-04 at 4 11 21 PM](https://github.com/user-attachments/assets/faa96e6b-9ac3-44c9-8629-cdfa81e8847f)
![Screenshot 2024-12-04 at 4 11 40 PM](https://github.com/user-attachments/assets/b1e4eeec-2135-42d6-b8a5-c84229d52a85)
![Screenshot 2024-12-04 at 4 11 58 PM](https://github.com/user-attachments/assets/c460bf7c-b651-4e0c-a44e-daf8fade2b8c)

<p> At the bottom of the osTicket installation page , you'll see links that allow you access the osTicket portal and the webpage used to create a help desk ticket.</p>

![Screenshot 2024-12-04 at 4 12 22 PM](https://github.com/user-attachments/assets/b3eefc12-db6b-4fb0-96ee-352ddcabfcab)

![Screenshot 2024-12-04 at 4 12 43 PM](https://github.com/user-attachments/assets/f5fde552-28eb-45b0-be0c-071235bfacfc)
![Screenshot 2024-12-04 at 4 16 11 PM](https://github.com/user-attachments/assets/ad8eaeed-2d92-44ed-9645-65831e56738c)

![Screenshot 2024-12-04 at 4 16 44 PM](https://github.com/user-attachments/assets/81ce4d0d-94f5-46de-8ec1-a1bdf70eba62)





