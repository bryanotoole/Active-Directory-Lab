# Active-Directory-Lab

## Description
- Created a domain controller virtual machine based on Microsoft Server 2019 ISO (Domain Controller) and a Windows 10 (Windows 10 ISO) virtual machine to serve as the client (CLIENT1)
- Set up an internal and external network for the Domain Controller virtual machine serve as a bridge between the internet, DC, and CLIENT1
- Created an admin user (self) within mydomain.com (a-botoole@mydomain.com) to manage the other users within the Active Directory
- Ran a PowerShell script to upload 1,000 users into Active Directory
- Successfully tested and confirmed a connection between the Domain Controller and CLIENT1 (7)
- Confirmed CLIENT1’s address lease was valid for the appropriate period of time (8)
- Modified Password Policies from default to meet organizational requirements (21)
- Enabled Account Lockout Policies to meet organizational requirements (20)
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
The purpose of this lab is to simulate setting up a basic virtual network for an organization and managing users within Active Directory. The lab demonstrate a basic understanding of virtual network setup and Active Directory functionality. The prograss of this lab is outlined in the Description above and displayed in the Screenshots below.
  
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
Figure 9: Lease for CLIENT1 confirmed from DHCP within the Domain Controller.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%208.%20Lease%20For%20CLIENT1%20User%20From%20DHCP%20View%20In%20Domain%20Controller.PNG"/> <br />
<br />
