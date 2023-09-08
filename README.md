# SQL_filters
<h1>Lab 4</h1>

<h2>Description</h2>
Scenario<br>
In this scenario, I am investigating a recent security incident.<br>

I need to gather information about login attempts for certain dates and times. This will help in resolving a security incident.<br>

Here’s how I will do this task:<br> First, you’ll retrieve login events made after a certain date.<br>Second, I will narrow the focus of the search to filter logins in a date range.<br> Third, I will investigate logins that were made at certain times.<br> Finally, I will filter login attempts based on their event IDs.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash shell</b> 
- <b>SQL</b>

<h2>Environments Used </h2>

- <b>Qwiklabs (Provided by Coursera [Google Cybersecurity course])</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch and Start : <br/>
<img src="https://imgur.com/dr3X6nt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/tLpdGe7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve login attempts after a certain date<br>
  1. retrieve data for login attempts made after '2022-05-09'.<br>
  2. retrieve data for login attempts that were made on or after '2022-05-09'.<br>
  <br/>
<img src="https://imgur.com/USTSWjb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/FGCV4IK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/1gMavKy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve logins in a date range (between '2022-05-09' and '2022-05-11'.) <br/>
<img src="https://imgur.com/eJQdbkX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/i185Zij.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Investigate logins at certain times<br>
 1. retrieve data for login attempts made before '07:00:00'.<br>
 2. return logins between '06:00:00' and '07:00:00'.
  <br/>
<img src="https://imgur.com/xjYANVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5ZnxbeM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Investigate logins by event ID<br>
 1. return login attempts with event_id greater than or equal to 100.<br>
 2. return only login attempts with event_id between 100 and 150.<br>

<img src="https://imgur.com/sVnybL6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://imgur.com/WJIHNFU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
