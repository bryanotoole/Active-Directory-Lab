# Active Directory Lab

## Description
- Created a domain controller virtual machine based on Microsoft Server 2019 ISO (Domain Controller) and a Windows 10 (Windows 10 ISO) virtual machine to serve as the client (CLIENT1)
- Set up an internal and external network for the Domain Controller virtual machine serve as a bridge between the internet, DC, and CLIENT1
- Created an admin user (self) within mydomain.com (a-botoole@mydomain.com) to manage the other users within the Active Directory
- Ran a PowerShell script to upload 1,000 users into Active Directory
- Successfully tested and confirmed a connection between the Domain Controller and CLIENT1
- Confirmed CLIENT1’s address lease was valid for the appropriate period of time
- Modified Password Policies from default to meet organizational requirements
- Enabled Account Lockout Policies to meet organizational requirements
- Simulated a new user (Humbleton Fouse) joining the organization, prompting them to have their default password changed upon their first login
- After 3 failed login attempts, reset and unlocked Leonel Cavalier’s password according to organizational policy


## Skills Learned
- Virtual network setup
- Active Directory management
- PowerShell Syntax
- Account and Password Policy Configuration


## Tools & Technology Used
- Oracle VirtualBox
- Microsoft Server 2019
- Microsoft Active Directory
- PowerShell

##  Background
The purpose of this lab is to simulate setting up a basic virtual network for an organization and managing its users within Active Directory. This lab demonstrate a basic understanding of virtual network setup and Active Directory functionality. The progress of this lab is outlined in the Description above and displayed in the Screenshots below.
  
## Screenshots

<p align="center">
Figure 1: Virtual machine setup in Oracle VirtualBox.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2025.%20Virtual%20Machines%20Used.PNG"/> <br />
<br />
<p align="center">
Figure 2: Virtaul network diagram serving as the foundational setup for this lab. <br/>
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%20Network%20Diagram.PNG"/> <br />
<br />
<p align="center">
Figure 3: Admin user created within the Domain controller virtual machine.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%202.%20Admin%20User%20Created%20Within%20Domain%20Controller%20Virtual%20Machine.PNG"/> <br />
<br />
<p align="center">
Figure 4: PowerShell script used to upload organizational 1,000 users into the domain.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%204.%20PowerShell%20Script%20to%20Create%201000%20Users.PNG"/> <br />
<br />
<p align="center">
Figure 5: PowerShell view of user creation files before running.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%205.%20PowerShell%20View%20of%20User%20Creation%20Files%20Before%20Running.PNG"/> <br />
<br />
<p align="center">
Figure 6: Users shown in AD after PowerShell upload.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%206.%20Users%20Shown%20In%20AD%20After%20PowerShell%20Upload.PNG"/> <br />
<br />
<p align="center">
Figure 7: CLIENT1 virtual machine Command Prompt showing confirmed connection with mydomain.com.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%207.%20CLIENT1%20Host%20VM%20IPConig%20Setup.PNG"/> <br />
<br />
<p align="center">
Figure 8: Lease for CLIENT1 confirmed from DHCP within the Domain Controller.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%208.%20Lease%20For%20CLIENT1%20User%20From%20DHCP%20View%20In%20Domain%20Controller.PNG"/> <br />
<br />
<p align="center">
Figure 9: Password Policy settings configured to meet organizational requirements.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2021.%20Changed%20Default%20Password%20Policies.PNG"/> <br />
<br />
<p align="center">
Figure 10: Account Lockout Policy setting configured to meet organizational requirements.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2020.%20Configured%20Account%20Lockout%20Attempts.PNG"/> <br />
<br />
<p align="center">
Figure 11: Password Policy settings configured to meet organizational requirements.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2021.%20Changed%20Default%20Password%20Policies.PNG"/> <br />
<br />
<p align="center">
Figure 12: New user Humbleton Fouse created wuthin AD.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2011.%20New%20User%20Humbleton%20Fouse.PNG"/> <br />
<br />
<p align="center">
Figure 12: New user Humbleton Fouse created wuthin AD.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2011.%20New%20User%20Humbleton%20Fouse.PNG"/> <br />
<br />
<p align="center">
Figure 13: Humbleton Fouse next logon password change setting enabled.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2012.%20Humbleton%20Fouse%20Next%20Logon%20Password%20Change%20Setting%20Enabled.PNG"/> <br />
<br />
<p align="center">
Figure 14: Humbleton Fouse password change prompt when attempting to login to CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2014.%20Humbleton%20Fouse%20Password%20Change%20Prompt.PNG"/> <br />
<br />
<p align="center">
Figure 15: Successful password change for Humbleton Fouse while attempting to login to CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2015.%20Successful%20Password%20Change%20For%20Humbleton%20Fouse.PNG"/> <br />
<br />
<p align="center">
Figure 16: Successful logon for Humbleton Fouse into CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2016.%20Humbleton%20Fouse%20Successful%20Signon%20After%20Password%20Change.PNG"/> <br />
<br />
