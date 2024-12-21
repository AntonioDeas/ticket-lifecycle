<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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

In this project, I start by cleaning up the departments. I change the SysAdmins department to a Top-Level Department and DELETE the Maintenance department. To do this, log in as admin, go to Agents > Departments, select Maintenance, click More, then Delete.

Go to http://localhost/osTicket and open a new ticket.

<h2>Intake</h2>


<p>
  <img width="450" alt="Create ticket main page" src="https://github.com/user-attachments/assets/457648f8-572d-48be-b189-56035f51246e" />
  
   Online Banking Ticket

<img width="450" alt="Creating ticket (mobile banking system down)" src="https://github.com/user-attachments/assets/d49c40c7-86c7-4da7-a993-663c96e9e613" />
 
  Adobe Ticket

<img width="450" alt="Creating ticket (adobe upgrade)" src="https://github.com/user-attachments/assets/a4749f79-37cc-45ca-9399-4e436fe35ea4" />
  
  CFO Ticket

<img width="450" alt="CFO ticket creating" src="https://github.com/user-attachments/assets/b6bbe0c2-4ae5-4da2-9054-3c00db7e0696" />


</p>
<p>
I start by creating tickets as an end-user to simulate real-world scenarios, such as reporting a system outage or a broken device. Each ticket is submitted to reflect common issues that need to be tracked and resolved.
</p>
<br />

<h2>Assignment and Communication</h2>
    Online Banking Ticket
<p>
<img width="400" alt="Banking ticket SLA" src="https://github.com/user-attachments/assets/e875a4ae-c70a-4226-aecd-9a8292a0f8f6" />
<img width="400" alt="Banking ticket team assign" src="https://github.com/user-attachments/assets/48914e7e-268a-4a01-b55c-fe108a6a2e31" />
<img width="400" alt="Banking ticket assignee" src="https://github.com/user-attachments/assets/b9b65147-44e1-4419-9bbb-9c3864930847" />
<img width="400" alt="Banking ticket help topic update" src="https://github.com/user-attachments/assets/b20eaffe-192e-4b52-bf66-176a09253f45" />
<img width="400" alt="Banking ticket priority setting" src="https://github.com/user-attachments/assets/441e98f4-fe92-4913-ab9a-2a58c870678f" />
</p>
    Adobe Ticket
<p>
<img width="450" alt="Adobe ticket SLA plan" src="https://github.com/user-attachments/assets/c1fa3d9d-205c-4178-95e1-bbf698dd3915" />
<img width="450" alt="Adobe ticket assignee" src="https://github.com/user-attachments/assets/aac82811-8388-440c-ab43-50adb2df2a03" />
</p>
    CFO Ticket
<p>
<img width="450" alt="CFO SLA plan" src="https://github.com/user-attachments/assets/3cab5573-7d7e-427d-b566-452130a8874d" />
<img width="450" alt="CFO ticket assignee" src="https://github.com/user-attachments/assets/00c55c88-a43f-47fd-9329-4e5c78372046" />
<img width="450" alt="CFO ticket priority level" src="https://github.com/user-attachments/assets/aaa10f99-4228-475b-a3da-c63994168c1e" />
</p>

<p>
As a Help Desk Agent, I review each ticket’s properties, including priority, department, SLA, and assigned personnel. I assign the appropriate values, such as setting high-priority tickets to Sev-A with strict SLAs and routing them to the relevant departments. I also adjust permissions to demonstrate how ticket visibility changes based on roles.

</p>
<br />

<h2>Working the Issue</h2>

Online Banking Ticket
<p>
<img width="400" alt="Banking ticket message thread update" src="https://github.com/user-attachments/assets/58c91a49-6d16-4721-abce-5f99af0a2e76" />
<img width="400" alt="Banking ticket post reply" src="https://github.com/user-attachments/assets/b6bcf9ce-7786-4732-b1b7-7eb058ba8458" />
<img width="400" alt="Banking ticket post reply 2" src="https://github.com/user-attachments/assets/60397a7a-e500-4240-b0fc-eb11cb1bb3cf" />

Adobe Ticket

<img width="400" alt="Adobe ticket post thread 2" src="https://github.com/user-attachments/assets/35c7a32f-e06c-4c15-855e-ab09c50dd5b3" />
<img width="400" alt="Adobe ticket post thread 3" src="https://github.com/user-attachments/assets/41b247e7-039c-4e87-9455-350ac056fab4" />

CFO Ticket

<img width="550" alt="CFO ticket thread post" src="https://github.com/user-attachments/assets/0759b970-fbad-4392-b843-bbfa4dca253e" />


</p>
<p>
After assigning the tickets, I work on resolving the issues. For example, I troubleshoot and resolve the reported problems, document updates in the ticket, and communicate progress with the end-user to keep them informed.</p>
<br />

<h2>Resolution</h2>


<p>
<img width="450" alt="Banking ticket closing ticket" src="https://github.com/user-attachments/assets/bd694649-3b0b-45de-80c6-dc705b009cdc" />
  <img width="450" alt="Adobe ticket closing" src="https://github.com/user-attachments/assets/13be43fb-2b58-4c9b-b418-249da706b886" />
  <img width="450" alt="CFO ticket closing" src="https://github.com/user-attachments/assets/45eae0c6-ef61-4ad8-b760-99c87fec842f" />


</p>
<p>
Finally, I close the tickets after completing the required tasks and verifying the solutions. I document the resolution in detail, ensuring the end-user is notified, and confirm that the issue is fully resolved before marking it as complete.
</p>
<br />
