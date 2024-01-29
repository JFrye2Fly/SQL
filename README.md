# SQL

<h1>Exploring failed login attempts by departments, country and more!</h1>


<h2>Description</h2>
Project consists of using different SQL operators to extract the right information. This project was part of the Google CyberSecurity Certificate program in which I had to explore failed login attempts based on time of day, department, and country location. I also searched for a list of offices in the Marketing department that followed the pattern "East***." by using the LIKE operator. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>SQL (Structured Query Language)</b> 

<h2>Program walk-through:</h2>

<p align="center">
Search for failed login attempts after 10pm. Success='0' means that the login attempt was indeed a failed one. <br/>
<img src="https://i.imgur.com/4hyry1C.png"/>
<br />
<br />
This SQL entry searches all entries from the log_in_attempts table where the Country does not start with "Mex". The LIKE operator and % are used in conjunction to determine a pattern. Mex% means any word that starts with "Mex". <br/>
<img src="https://i.imgur.com/704utme.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using the OR operator to select all entries from the employees table where the employee is in the finance OR sales department. <br/>
<img src="https://i.imgur.com/3Wjl9N5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Here I use the AND operator with the Like % operator to choose all entries from the employees table that work in the MARKETING department and whose office starts 
 with "East"<br/>
<img src="https://i.imgur.com/eu4VcSd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
