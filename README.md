<h1>Add AD Users Script</h1>



<h2>Description</h2>
<p>PowerShell ISE (Integrated Scripting Environment) is a graphical user interface (GUI) for writing, running, and debugging PowerShell scripts.</p>

<p>Steps for adding users via a PowerShell Script:</p>

1. From your server, click Start, right-click on Windows PowerShell ISE, hover to More, and click on “Run as administrator”<br>
2. At the User Account Control, at the “Do you want to allow this app to make changes to your device?”, click Yes.<br>
3. At the PowerShell screen (blue), type “Set-ExecutionPolicy Unrestricted”.<br>
4. At the Execution Policy Change window, click Yes to All.<br>
5. Change directory from C:\Windows\system32 to the path directory to where your script is located. Type “cd c:\users\a.vera\documents, and click Enter. (Note: For Lab purposes, I am saving 2 files under the Server’s Documents folder)<br>
6. Minimize PowerShell ISE, then at the server, click on File Explorer, navigate to the “Documents” folder.<br>
7. Right-click the screen and hover to “New”, and click on Text Document. Name the file “Employees1”.<br>
8. Open the Employees1 file and enter 8 names (first name last name) format. For lab purposes, I am using the following:<br>
Aurelio Vera<br>
Ian Martin<br>
Lucy Rivers<br>
Michael Jordan<br>
Nancy Smith<br>
Peter Parker<br>
Tom Cruise<br>
Wendy Pak<br>
9. Save and close the file.<br>
10. Maximize PowerShell ISE, from the top menu click on File and New.<br>
11. Open the enclosed file named Create_AD_Users.ps1 (without running the script):<br>
12. Minimize PowerShell ISE, under Server Manager’s Dashboard, click on Tools and select Active Directory Users and Computers.<br>
13. The Active Directory Users and Computers windows opens up. On the left-side, expand mydomain.com.<br>
14. To see what goes on, split your Server screen with the 2 windows; PowerShell ISE and Active Directory Users and Computers.<br>
15. At the PowerShell ISE, click on the “Run Script” icon (green play button). The script will run a create 8 users.<br>
16. At the Active Directory Users and Computers, click on the Refresh icon (green circle).<br>
17. On the left side, click on the _USERS folder, notice your 8 users were added.<br>
18. Proceed to the section titled “Steps to Create the Virtual Client (Windows 11).
<br />

<h2>Utilities Used</h2>

- <b>PowerShell</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (24H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch PowerShell ISE: <br/>
<img src="https://i.imgur.com/k3Bsmr9.png" height="80%" width="80%""/>
<br />
<br />
Script added the desired Users:  <br/>
<img src="https://i.imgur.com/m7A4h9e.png" height="80%" width="80%""/>
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
