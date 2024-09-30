![68747470733a2f2f692e696d6775722e636f6d2f436c7a6a3758732e706e67](https://github.com/user-attachments/assets/39618c7d-3ba9-4fc7-9c4c-4d808e415ee9)
                                                                 
                                                        𝐨𝐬-𝐓𝐢𝐜𝐤𝐞𝐭 𝐏𝐨𝐬𝐭 𝐈𝐧𝐬𝐭𝐚𝐥𝐥 𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧
                                        
 
 This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.                                       
                                               𝐕𝐢𝐝𝐞𝐨 𝐃𝐞𝐦𝐨𝐧𝐬𝐭𝐫𝐚𝐭𝐢𝐨𝐧  
           https://www.youtube.com/watch?v=4kEQtECcO-U                                    

 𝐄𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭𝐬 𝐚𝐧𝐝 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐢𝐞𝐬 𝐔𝐬𝐞𝐝    
 *Microsoft Azure (Virtual Machines/Compute)
 
 *Remote Desktop

*Internet Information Services (IIS)

𝐎𝐩𝐞𝐫𝐚𝐭𝐢𝐧𝐠 𝐒𝐲𝐬𝐭𝐞𝐦𝐬 𝐔𝐬𝐞𝐝

*Windows 10 (21H2)

𝐏𝐨𝐬𝐭-𝐈𝐧𝐬𝐭𝐚𝐥𝐥 𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬

Login to the osTicket Admin Panel

Configure Roles

Configure Departments

Configure Teams

Configure Help Topics

𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧 𝐒𝐭𝐞𝐩𝐬
ogin to the osTicket Admin Panel. Below displays the tickets for admin/helpdesk User Interface (UI) that will reflect the tickets that are created by the End User http://localhost/osTicket/scp/login.php

![68747470733a2f2f692e696d6775722e636f6d2f757a41413733662e706e67](https://github.com/user-attachments/assets/b5dbbbc7-9c51-4f1c-9c7e-4ac5f3e83889)

𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐑𝐨𝐥𝐞𝐬
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
<img width="960" alt="admin_agents_roles" src="https://github.com/user-attachments/assets/6d253168-84b2-4ad7-86d0-44e104870f6d">
𝐀𝐝𝐦𝐢𝐧 𝐏𝐚𝐧𝐞𝐥 > 𝐀𝐠𝐞𝐧𝐭𝐬 > 𝐑𝐨𝐥𝐞𝐬

𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐃𝐞𝐩𝐚𝐫𝐭𝐦𝐞𝐧𝐭𝐬
<img width="958" alt="admin_agents_departments" src="https://github.com/user-attachments/assets/f9ba7f08-e61b-4958-b2d9-2a703bb3eb69">
𝐀𝐝𝐦𝐢𝐧 𝐏𝐚𝐧𝐞𝐥 > 𝐀𝐠𝐞𝐧𝐭𝐬 > 𝐃𝐞𝐩𝐚𝐫𝐭𝐦𝐞𝐧𝐭𝐬

𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐓𝐞𝐚𝐦𝐬
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
![admin_agents_teams](https://github.com/user-attachments/assets/a77f9e32-f265-4d25-9705-4cd4135e0a0e)
𝐀𝐝𝐦𝐢𝐧 𝐏𝐚𝐧𝐞𝐥 > 𝐀𝐠𝐞𝐧𝐭𝐬 > 𝐓𝐞𝐚𝐦𝐬




