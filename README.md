<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket - Ticket Life Cycle</h1>
This tutorial continues from the Post Install Configuration lab and outlines the Ticket Life Cycle in osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  
<h2>Ticket Life Cycle Objectives </h2>

-Intake
-Assignment and Communication
-Working the Issue
-Resolution

<h2>Ticket Life Cycle Stages </h2>


<p>

<br />

![image](https://github.com/user-attachments/assets/991b8f89-4436-4c4a-8c08-337f6619b255)
![image](https://github.com/user-attachments/assets/9f321774-b577-4c08-9bd5-389252e49e7a)


</p>
<p>
The first Configuration I am going to demonstrate is Departments. In the same row as settings select Agents and in the row below Settings and Agents select Departments. Now click Add new Department. Now we will enter settings
</p>
<br />

![image](https://github.com/user-attachments/assets/5310143d-e0cc-4b95-a8b9-e090cc61eeed)

<p>
It will now bring up a settings page for us to enter the settings information about this department. I will enter in a bunch of sample settings and then click on Access. When we click Access this is where we would select the Agents assigned to this department but we haven't created any yet so there nothing to put. I will no click create Department and it will take you back to the departments screen before I clicked Add New Department. I can now see the Department for IT has been created.
</p>
<br />

![image](https://github.com/user-attachments/assets/c805ff52-3ed1-4c30-99ec-ebece189fc20)
![image](https://github.com/user-attachments/assets/43bfa9d5-21db-4999-b738-391e38cc51f4)
![image](https://github.com/user-attachments/assets/13061899-72aa-4998-9ebf-9f5588469f33)

<p>
Now on this same screen in the tab where we selected Departments we will now select Agents and click Add New Agent. Now here is where an Agent is added and you would add the employees information, access, and permissons. From here you can select what permission or access they have to the ticketing system. You can even assign them to certain teams which we will be creating later. This is useful for reasons like if you need this employee to be an admin and oversee and edit Users and Groups and Permissions or maybe this is a brand new employee who should only see and work on tickets assigned to them or their team.
</p>
<br />

<p>
For this example I will be making the Agent John Doe and give him Administartor Status. After the account info has been entered and status set we will click on Access. Now I see it lets me select a department for my Agent and what kind of Access they should be allowed. For this Lab I will choose the department I just made and give the Agent All Access. It even gives us an option to add this Agent to an additional department but for this lab we will just do one. Now I will select Permissions in the same row of tabs as Account and Access.
</p>
<br />

![image](https://github.com/user-attachments/assets/b4284514-a104-48fa-9e04-ad28107e2bbb)

![image](https://github.com/user-attachments/assets/83df74e5-7a18-4b00-9381-aa04001b9903)

<p>
For Permissions it will display 4 tabs under the previous row of tabs and it shows Users, Organizations, Knowledgebase, and Miscellaneous. To show each tab with each option for permissions would be tedious so I will show a screen shot of just the User tab permissions and just know each tab has about the same list with checkmarks to select if you want your agent to have certain Permissions. After the permissions have been selected we will now proceed to the Teams tab.
</p>
<br />

![image](https://github.com/user-attachments/assets/d514e7f1-da19-4128-a0a9-bdf7cf807fe4)

<p>
I have not yet created a team but there is a default team already made called Level 1 Support. For this lab I will select that one but will still proceed to make another Team later in this lab. After the Team is selected click on add and we are good to go and hit create on the bottom and create our first Agent!
</p>
<br />

![image](https://github.com/user-attachments/assets/1c5f0052-1962-45ec-bb27-844b87f40a5a)

