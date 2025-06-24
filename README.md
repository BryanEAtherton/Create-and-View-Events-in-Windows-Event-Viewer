# Windows Event Viewer Exercise 

<p align="center">
<img src="https://i.imgur.com/Yjq38L7.jpeg"/>
</p>

<h1>Create and View Events in Windows Event Viewer</h1>
Here we will create failed login events using SSMS in the Windows VM and observe them in Windows Event Viewer.

<h2>Operating System Used</h2>
-Windows 10

<h2>Environments and Technologies Used</h2>

- SQL Server Management System (SSMS)
- Windows Event Viewer



<h2>Create and View Events in Windows Event Viewer </h2>

<br />


<p>
1. Starting from the end of the Install SSMS section in Azure Honeynet VM Setup, log out of the SSMS app. 
</p>
<p>
<img src="https://i.imgur.com/shFG37A.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

  
[Click here to view the Install SSMS section](https://github.com/BryanEAtherton/Install-SSMS)

<br />

<p>
2. Attempt to reconnect to the server and intentionally fail using incorrect passwords. Do this at least 3 times.
</p>
<p>
<img src="https://i.imgur.com/vAt6M9b.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

<p>
 3. Open Windows Event Viewer
</p>
<p>
<img src="https://i.imgur.com/y72gJDw.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

<p>   
4. Under Windows Logs, Select Application.
<p>
<img src="https://i.imgur.com/WJjbw1j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. Here we can see our failed logon attempts and more details about these events in the bottom portion of the window.
<p>
<img src="https://i.imgur.com/F7e5bMk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

[Click here to return to my Github Homepage](https://github.com/BryanEAtherton)

<br />

