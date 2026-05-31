<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://www.youtube.com/playlist?list=PLoowYzuxGQ0DgyFrhbszdnxY7VwvCH3H8)

<h2>Description</h2>
In this lab series, I walk through the everyday tasks that a Help Desk Support Technician handles in the real world, using Active Directory. I demonstate user account management, password resets, permissions, troubleshooting access issues, and a whole lot more. Everything you'd expect someone in a Help Desk role to perform on day one. I wanted to go beyond just listing skills on a resume — I wanted to actually show them in action. I wanted to demonstrate the process from HR onboarding tickets that initiated the workflow before any Active Directory work begins to the offboarding process of disabling an employee account.
<br />


<h2>Objectives</h2>

- <b>Create and configure new user accounts in Active Directory</b> 
- <b>Build an Organizational Unit structure that mirrors a real company</b>
- <b>Manage Security Group membership to control resource access</b>
- <b>Simulate and resolve a common account lockout scenario</b>
- <b>Demonstrate proper employee offboarding procedures</>


<h2>Tools & Technologies Used </h2>

- <b>Windows Server 2022</b>
- <b>Active Directory Users and Computers (ADUC)</b>
- <b>VirtualBox</b>
- <b>ServiceNow (for ticket creation)</b>


<h2>Environments Used </h2>
My lab was hosted on my Asus computer using the Virtualbox hypervisor. I set up a Microsoft Windows 2022 server, and 2 Client Computers (only one was used during this lab). 


- <b>Oracle VirtualBox Manager Hypervisor</b> (7.2.0)
- <b>Microsoft Windows Server 2022</b> (64-bit)
- <b>2 Client Hosts Windows 11 Pro OS</b> (25H2)


<h2>Skills Demonstrated:</h2>

- <b>User account creation and configuration</b> 
- <b>Organizational Unit design and management</b> 
- <b>Security Group creation and membership management</b>
- <b>Account lockout resolution and password reset</b> 
- <b>Account deprovisioning and offboarding best practices</b>
<br />
  
<h2>Program Walk-through:</h2>
<br />
<h2>HR Onboarding Workflow:</h2>
This section shows the onbarding tickets created in ServiceNow that initiated the Active Directory workflow
<br />
<br />

<p align="center">
Step 1: Creating the Onboarding Ticket Request <br/>
<img src="https://imgur.com/FrBuzPj.png" height="80%" width="80%" alt="Creating Onboarding Ticket Request Steps"/>
<br />
 <img src="https://imgur.com/Q50KidN.png" height="80%" width="80%" alt="Creating Onboarding Ticket Request Steps"/>
<br />
Step 2: Onboarding Ticket References <br/>
<img src="https://imgur.com/W2WQRwf.png" height="80%" width="80%" alt="Creating Ticket Reference Steps"/>
<br />
<img src="https://imgur.com/J6bTWAI.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/u0XZPGi.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/cGqRbKl.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/oxLptwO.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/2smExU2.png" height="80%" width="80%" alt="Creating Ticket Reference Steps"/>
<br />
<img src="https://imgur.com/vDdMV2Q.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/8n6igzR.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/c1JWY2S.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />
<img src="https://imgur.com/aMCpTEg.png" height="80%" width="80%" alt="Creating Ticket Reference  Steps"/>
<br />



<br />
<h2>Active Directory Workflow:</h2>


<p align="center">
Step 1: Creating the OU Structure <br/>
<img src="https://imgur.com/XlEMtnS.png" height="80%" width="80%" alt="Creating OU Structure Steps"/>
<br />
<br />
Step 2: Creating Security Groups  <br/>
<img src="https://imgur.com/nzSNRVo.png" height="80%" width="80%" alt="Security Group Steps"/>
<br />
 <img src="https://imgur.com/T9G5UUa.png" height="80%" width="80%" alt="Security Group Steps"/>
<br />
 <img src="https://imgur.com/5MP8HSN.png" height="80%" width="80%" alt="Security Group Steps"/>
<br />
<br />
Step 3: Creating the New User Account <br/>
<img src="https://imgur.com/lu8X4KR.png" height="80%" width="80%" alt="Creating the new user Step"/>
<br />
<br />
Step 4: Configuring Account Properties  <br/>
<img src="https://imgur.com/4YcaRjP.png" height="80%" width="80%" alt="Configuring Account Properties Step"/>
<br />
<br />
Step 5: Adding the User to a Security Group  <br/>
<img src="https://imgur.com/d9HIEZA.png" height="80%" width="80%" alt="Adding User to Security Group Steps"/>
<br />
<br />
Step 6: Simulating and Resolving an Account Lockout  <br/>
<img src="https://imgur.com/oCxPbhk.png" height="80%" width="80%" alt="Simulating and Resolving Account Lockout Steps"/>
<br />
 <img src="https://imgur.com/p0GtCsn.png" height="80%" width="80%" alt="Simulating and Resolving Account Lockout Steps"/>
<br />
 <img src="https://imgur.com/5Bi7EFT.png" height="80%" width="80%" alt="Simulating and Resolving Account Lockout Steps"/>
<br />
 <img src="https://imgur.com/OBiR5fi.png" height="80%" width="80%" alt="Simulating and Resolving Account Lockout Steps"/>
<br />
 <img src="https://imgur.com/o9VLRWB.png" height="80%" width="80%" alt="Simulating and Resolving Account Lockout Steps"/>
<br />
<br />
Step 7: Disabling the Account — Employee Offboarding  <br/>
<img src="https://imgur.com/UugGUvt.png" height="80%" width="80%" alt="Disabling the Account Steps"/>
<br />
<img src="https://imgur.com/fTutntr.png" height="80%" width="80%" alt="Disabling the Account Steps"/>
<br />
<img src="https://imgur.com/Mw0PRKM.png" height="80%" width="80%" alt="Disabling the Account Steps"/>
<br />
<img src="https://imgur.com/EWA6iRa.png" height="80%" width="80%" alt="Disabling the Account Steps"/>
<br />
<img src="https://imgur.com/6lVyliV.png" height="80%" width="80%" alt="Disabling the Account Steps"/>
<br />
<br />



 
<br />
 


 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
