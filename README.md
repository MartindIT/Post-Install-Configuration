<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

![image](https://github.com/MartindIT/post-install-config/assets/151476834/55eb4625-dfda-4b10-b1b1-9a8d80424fbb)
**1.) Once were in the front page of Osticket we will click on the admin pannel and begin.** 

![image](https://github.com/MartindIT/post-install-config/assets/151476834/733df689-0293-43d2-995c-ab55975c5d8c)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/e1339b65-e129-4ecf-81dd-a42123fe6b55)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/8b21f93b-7554-45d9-a5a7-c0cc26f1fbe2)
**2.) First we will create a role called "Supreme Admin" Then add permissions (we will give this role all permissions just for the sake of this project and so that we can do everything without problems)** 

![image](https://github.com/MartindIT/post-install-config/assets/151476834/1752fb43-7a2f-4898-a1bb-ceae72ea1315)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/e11fca70-8bec-405d-9844-589f35660f91)
**3.) Admin Pannel -> Agents -> Deparments**

**We will add a new Department called "System Administrators"**

![image](https://github.com/MartindIT/post-install-config/assets/151476834/fc5b51ac-874d-436d-bfa4-3fa522397499)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/fde826c7-05fe-4aca-bcb2-39ccc3c3ebbe)
**4.) Admin Pannel -> Agents -> Teams**

**We can change the name of the department I will name it "level II Support since level I is here by default we can add agents once we create them but for now you can add yourself.**

**Teams allow you to pull agents from different Departments and organize them to handle a specific issue**




![image](https://github.com/MartindIT/post-install-config/assets/151476834/c6d7dad1-c598-4093-9fa4-5dfd89bb243d)
**5.) Admin Pannel -> Settings -> User Settings**

**Make sure to check if this box is unchecked so that users can create tickets anonymously**

![image](https://github.com/MartindIT/post-install-config/assets/151476834/e4ef2a3c-a1a7-4d19-98cc-b8b6397c597d)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/95c14d2f-54d7-43d1-8640-9d42dc07913a)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/1c63355b-50df-41a0-96ca-391caf0ac84a)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/f3b5e405-dc93-48a0-82cb-3a225a038798)
**6) Admin Pannel -> Agents -> Add New**

**Agents are the Help desk professionals that will resolve the tickets we create so we will create a fake agent called "Jane doe" and give them permissions and add them to the departments and teams we already made.** 

![image](https://github.com/MartindIT/post-install-config/assets/151476834/eccd1a3c-d897-48ad-a786-f78e5b5394d9)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/f30e2f8f-5f42-4cf3-b7c4-441390723b18)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/0a0f0501-8503-48fd-a712-3bf7a95c662b)

**7.) Agent Pannel -> Users -> Add new**

**The users are the Customers or the people you will be providing support for in this case we will create fake users such as Karen you can make as many as you need.**

![image](https://github.com/MartindIT/post-install-config/assets/151476834/8b0223d2-7f7c-41e3-b50e-d24084c5fd9a)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/611732f8-5c29-4984-b8a3-01b51ace4e1b)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/4d0cba2b-2c59-4733-bb27-6c7e19634295)
**8.) Admin Pannel -> Manage -> SLA**

**SLA is a plan for the length of time in which the help desk administrator expects tickets to be closed. In this case we will make three different SLA Plans with different severitys and schedules** 

![image](https://github.com/MartindIT/post-install-config/assets/151476834/9d2657e1-762b-4c70-b907-392acbe2b137)
![image](https://github.com/MartindIT/post-install-config/assets/151476834/1ea94c2d-9ae5-46eb-ba49-e862960e9e87)
**9.) Admin Pannel -> Manage -> Help Topics**

**When the end Users are filling out tickets they can choose what they need help with such as subjects and topics** 

**In this case we added Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset for our help topics and this will be seen by Karen or as many of the fake Users we made.
Once were done with this setup we can begin with the next part of Osticket where we will see and experience what we created through Osticket.**








