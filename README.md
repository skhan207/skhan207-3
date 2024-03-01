<h1>Active Directory Project</h1>
<img src="https://i.imgur.com/rNWqVVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Description</h2>
In this project I demonstrate how to create an Home lab Active Directory Environment using Oracle Virtual Box. Configuring and running this project will definitlry help develop an understanding of how active directory and windows networking works.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch virtual box and start setting up the virtual machines: <br/>
<img src="https://i.imgur.com/t7BwJFE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add an extra adapter for the domain controller:  <br/>
<img src="https://i.imgur.com/mnGAFx7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Instal the windows server(server will restart several times during this stage): <br/>
<img src="https://i.imgur.com/VSibNeL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Insert guest additions cd image:  <br/>
<img src="https://i.imgur.com/TsY72aN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install active directory domain services:  <br/>
<img src="https://i.imgur.com/kCAfeN0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create domain for active directory:  <br/>
<img src="https://i.imgur.com/TkU7Udm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create organization unit to put admin account in:  <br/>
<img src="https://i.imgur.com/PbVLG47.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup DCHP scope:  <br/>
<img src="https://i.imgur.com/f0tLqBW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download source code for powershell script and names folder :  <br/>
<img src="https://i.imgur.com/DoUbno4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run the code. It will cucle 1000 times and create new users in active directory while it cycles through. After this, you can observe your home lab :  <br/>
<img src="https://i.imgur.com/2tzXrgr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!># skhan207-3
