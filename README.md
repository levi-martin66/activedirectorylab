# Active Directory Lab


<h2>Description</h2>
Setting up a Basic Home Lab Running Active Directory (Oracle VirtualBox) and Adding Users with PowerShell
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory</b>
- <b>Windows Server</b>
- <b>Virtualization</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Creating the DC: <br/>
<img src="https://imgur.com/C0Nat9Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
<br />
Starting up the VM that is acting as our DC:  <br/>
<img src="https://imgur.com/KH6T70e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Creating the domain and roles: <br/>
<img src="https://imgur.com/ny0fV0U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Here are the roles that I've added:  <br/>
<img src="https://imgur.com/Bm5pLyz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Creating the admin:  <br/>
<img src="https://imgur.com/NMc8ZOD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Here is the code I used in the PowerShell to add the users to our database:  <br/>
<img src="https://imgur.com/0RYFtHo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Here are the names being translated into separate usernames:  <br/>
<img src="https://imgur.com/kkUxjSP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
Here is me creating a client VM to simulate an employee using their own computer:  <br/>
<img src="https://imgur.com/lZjCpC9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
Here is the new client VM operating:  <br/>
<img src="https://imgur.com/lUoEwow.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
