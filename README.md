<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this tutorial we will be creating tickets as end users, observing all the ticket properties and responding to them as help desk professionals
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Log into your Windows Virtual Machine
- Open osTicket 
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h2>Log into your Windows Virtual Machine</h2>
First of all log into your Windows Virtual Machine, using Remote Desktop Connection and using your credentials. 
<p align left>
<img width="301" height="187" alt="image" src="https://github.com/user-attachments/assets/3662e595-8577-4868-a9b3-a66425c006f1" />
<img width="335" height="328" alt="image" src="https://github.com/user-attachments/assets/8026b64a-8710-41d0-a944-864ee3fa565d" />
<img width="289" height="302" alt="Screenshot 2025-11-28 142041" src="https://github.com/user-attachments/assets/449aa276-e07b-4355-b5fd-d69026a5c301" /># workflow

<h2>Open osTicket as Admin</h2>
In your Windows Virtual Machine click on the Admin/Analyst Login Page http://localhost/osTicket/scp/login.php and use your admin credentials previously created. 
<p align left>
<img width="1301" height="741" alt="image" src="https://github.com/user-attachments/assets/7d47b78f-f51c-4f22-92a4-cd7841e7efce" />
<img width="1900" height="691" alt="image" src="https://github.com/user-attachments/assets/9e5e5875-a8ff-418f-bc25-efaa6deb53ce" />

As an end-user, we are going to create the following ticket: entire mobile/online banking system is down
<p align left>
<img width="565" height="300" alt="Screenshot 2025-11-29 140607" src="https://github.com/user-attachments/assets/f699ac97-dfbe-42a3-acfc-308465dfb02e" />

As end user Karen we are going to create a ticket with the following information: email: karen@lognpacific.com, Full Name: Karen, Phone number: 516-244-4907, Help Topic: Report a Problem, Issue Summary: entire mobile/online banking system is down, and provide a bried description of the issue, then click on Create Ticket
<p align left>
<img width="300" height="368" alt="Screenshot 2025-11-29 141232" src="https://github.com/user-attachments/assets/7a9d86c0-ae95-4414-9f73-4cb74e2e24f3" />
<img width="400" height="837" alt="image" src="https://github.com/user-attachments/assets/e3f78279-bcaa-4e5f-b6f2-99b1498363f5" />

<h2>Intake</h2>
Then we are going to log into osTicket as Agent John (worker)
<p align left>
<img width="1378" height="737" alt="image" src="https://github.com/user-attachments/assets/4ee365db-09dc-4417-a516-58c6fece1f5d" />
<img width="1301" height="535" alt="image" src="https://github.com/user-attachments/assets/ff192bf1-6383-49e7-a8d7-8010fc48fe3b" />

Observe the ticket #242075, the priority has been set as normal, Department is Support, Ticket is Unassigned, the SLA was set as Defaul SLA. Review the ticket issue, per the summary it looks serious and if you can talk to them on the phone is best or reach out to them by an internal message by using Teams and ask them questions about the problem. We are going to modify the SLA, Priority and Assigned to an Agent/
<p align left>
<img width="518" height="335" alt="Screenshot 2025-11-29 142807" src="https://github.com/user-attachments/assets/6bc4ce99-3d81-49ea-bc80-18920a69f861" />

Change the SLA from Default to Sev-A
<p align left>
<img width="878" height="345" alt="image" src="https://github.com/user-attachments/assets/1a2ef70a-8753-4fa1-b64b-3177a31bf865" />

Update Help Topic from Report a Problem to Report a Problem/Business Critical Outage for more accuracy
<p align left>
<img width="882" height="348" alt="image" src="https://github.com/user-attachments/assets/5f1bfa9e-d1a4-4702-b817-10ae1b618147" />

<h2>Assignment and Communication</h2>
Assign ticket #242075 to Online Banking Team
<p align left>
<img width="877" height="340" alt="image" src="https://github.com/user-attachments/assets/972b6ff9-5032-418a-80ca-a5ef71a2f6b7" />

After all the updates from Agent John, this should be the updated ticket #242075. Log out from Agent John
<p align left>
<img width="1306" height="616" alt="image" src="https://github.com/user-attachments/assets/d8f17c50-26a2-4488-aa6f-b431f5cfc4da" />

<h2>Working the Issue</h2>
Then log in as Agent Jane because she is in the Online Banking Team and she will work the ticket
<p align left>
<img width="1562" height="838" alt="image" src="https://github.com/user-attachments/assets/7f7f1159-fe02-4d00-b950-c28965faa4ed" />
<img width="1296" height="546" alt="image" src="https://github.com/user-attachments/assets/55a46b83-ce0f-48c0-b67c-68b358715844" />

Usually the Departments have more than just one person, for that reason change from Online Banking to the Agent that will work the ticket
<p align left>
<img width="876" height="388" alt="image" src="https://github.com/user-attachments/assets/c0087791-1c03-425a-9bb2-7aa2a29cc6ac" />
<img width="1295" height="673" alt="image" src="https://github.com/user-attachments/assets/25a7218a-1413-4024-b0d1-40d5294c8688" />

You can make an update in the thread, and usually when this is done it will send a message or an email to all the people related in this thread
<p align left>
<img width="1289" height="867" alt="image" src="https://github.com/user-attachments/assets/ab3c53df-b897-44af-9332-816b08f34bd4" />
<img width="1292" height="912" alt="image" src="https://github.com/user-attachments/assets/190be681-9420-4bb3-ade5-6a2d7ec69a74" />
<img width="1280" height="909" alt="image" src="https://github.com/user-attachments/assets/6277c011-14eb-4472-9d4b-b59c3988b8db" />


You can see all the trail of reply from Agent John and Agent Jane
<p align left>
<img width="1087" height="913" alt="image" src="https://github.com/user-attachments/assets/6626c347-1ffc-4247-817a-21af2ca80d3b" />

And now that everything has been fixed, we can set ticket #242075 from Open to Resolved
<p align left>
<img width="518" height="269" alt="Screenshot 2025-11-29 151626" src="https://github.com/user-attachments/assets/5bd209af-5139-4837-968c-34c94bc531a5" />
<img width="1305" height="538" alt="image" src="https://github.com/user-attachments/assets/b16a5d55-3e7f-495b-8e74-0ce79293aabf" />

For this lab we have 3 tickets to create, after the first ticket have been resolved we are going to create a second ticket as Ken an end-user, create the following ticket
accounting department needs adobe upgrade, broken
<p align left>
<img width="517" height="335" alt="Screenshot 2025-11-29 152350" src="https://github.com/user-attachments/assets/b3f20658-1513-40f1-a7b2-b0746d3dd866" />
<img width="839" height="890" alt="image" src="https://github.com/user-attachments/assets/3821f508-e72b-4f4d-87a0-237ef7210c0e" />
<img width="845" height="540" alt="image" src="https://github.com/user-attachments/assets/eff2a42d-fefb-4c19-80ed-6d87bea7e4a8" />

<h2>Intake</h2>
Then we are going to log into osTicket as Agent John (worker)
<p align left>
<img width="558" height="538" alt="image" src="https://github.com/user-attachments/assets/6e970b92-8380-477e-a99a-0fa2369a8438" />
<img width="1295" height="511" alt="image" src="https://github.com/user-attachments/assets/02528d59-4845-4da6-ba94-94f78a9884cf" />

Inspect ticket #577334, the issue summary looks ambiguous, Agent John should contact Ken in order to get more information about the issue.
<p align left>
<img width="878" height="344" alt="image" src="https://github.com/user-attachments/assets/deee2969-433a-4ebb-9589-cd05327fd4ff" />

<h2>Assignment and Communication</h2>
Agent Jonh contact Ken and asked how many people have been affected by the issue and it turned out there are only 2 people in the Accounting Department, Agent John then suggest Ken to restart the computer because there were a lot of updates in Windows, Ken agrees to Agent John alternative to fix the issue and will call them after lunch to find out if that fix the issue
<p align left>
<img width="875" height="333" alt="image" src="https://github.com/user-attachments/assets/26783ec5-c78f-4f66-af0f-3d2fef6b4def" />

<h2>Working the Issue</h2>
John assigned the ticket to himself and is working the ticket
<p aling left>
<img width="1287" height="824" alt="image" src="https://github.com/user-attachments/assets/a30c5698-8b29-4c98-861c-202813818b4b" />

After a few hours end user Ken, called back to Help Desk and notified that issues have and everything is working fine, agent John make a note about call and resolved the ticket
<p align left>
<img width="1278" height="842" alt="image" src="https://github.com/user-attachments/assets/74874fc3-da9e-4ea7-b8a3-b53c05fe6088" />

<h2>Resolution</h2>
You can see the notes about the issue, John proceed to resolved the ticket.
<p align left>
<img width="1293" height="723" alt="image" src="https://github.com/user-attachments/assets/a6e9c1b5-daee-4a08-a1fa-8912ec70d50a" />
<img width="872" height="296" alt="image" src="https://github.com/user-attachments/assets/86e8a7c4-8307-445f-badc-fc9b45a809a6" />


Last ticket of this lab will be as an end-user Karen, create the following ticket: CFO’s laptop will no longer turn on

<p align left>
<img width="517" height="335" alt="Screenshot 2025-11-29 152350" src="https://github.com/user-attachments/assets/b3f20658-1513-40f1-a7b2-b0746d3dd866" />
<img width="945" height="902" alt="image" src="https://github.com/user-attachments/assets/50847a8d-4510-490d-b3ae-5e1a05d62501" />
<img width="952" height="602" alt="image" src="https://github.com/user-attachments/assets/a7184160-c95c-4949-a2fc-084887c4a4d4" />

<h2>Intake</h2>
Agent John, received the ticket from Karen regarding the CFO's issue, observe everything. He then change the priority of ticket #384932 to Emergency
<p align left>
<img width="875" height="336" alt="image" src="https://github.com/user-attachments/assets/1184432b-1888-4f34-92df-622b5c3406d6" />

Update the SLA from Default to Sev-B
<p align left>
<img width="875" height="340" alt="image" src="https://github.com/user-attachments/assets/16daafc8-5ba5-44c6-8a96-6720badb4d86" />

And assign himself the ticket to work it out
<p align left>
<img width="877" height="343" alt="image" src="https://github.com/user-attachments/assets/f433bc5a-aaa9-4ddf-931b-fd6061bfab7b" />
<img width="1288" height="700" alt="image" src="https://github.com/user-attachments/assets/5a4f5a3f-4281-49db-b03b-5b9d02e392cd" />

<h2>Assignment and Communication</h2>
John decided to call CFO because if he ping on Teams probably won't answer because his computer is not working or he can also reach out to Karen to fix the issue. John went to his office to find out more about the problem
<p align left>
<img width="1283" height="901" alt="image" src="https://github.com/user-attachments/assets/27c832fc-6aad-4858-9359-f37f5555b1db" />

<h2>Resolution</h2>
John brought new charger and now is successfully charging 
<p align left>
<img width="1289" height="826" alt="image" src="https://github.com/user-attachments/assets/49b08bbe-8e26-40a9-b4c6-55b14354ebd6" />

Ticket #384932 have been resolved by Agent John
<p align left>
<img width="879" height="306" alt="image" src="https://github.com/user-attachments/assets/87f4346a-2574-46af-a241-1efd06e529fd" />
<img width="1301" height="523" alt="image" src="https://github.com/user-attachments/assets/f73309f0-db27-4859-88e0-678710e24309" />


There can be more ways to intake the tickets but for the purpose of this lab we only use the online ticket, but customer can call directly help desk, send an email or start a chat to create a ticket. This conclude our Ticket workflow. 


