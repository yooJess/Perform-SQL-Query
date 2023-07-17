<h1>Creating and Managing Directory and Files in Linux</h1>

<h2>Description</h2>
In this project, we will be performing an SQL Query.<br/> 

<br/>

<h2>Project</h2>

<p align="left">
  <b>1. </b>We can start a simple SQL by using the 'SELECT' and 'FROM' Command to pull data by > "Selecting" all the data, "From" the specific table 'machines'.<br/>
  <br/>
<img src="https://i.imgur.com/DU8geVa.png" height="80%" width="80%" alt="SQL Select and From"/>
<br/>
<br/>
  Note:<br/>The 'SELECT' and 'FROM' are <b>not</b> case sensitive. But, the 'table names' <b>are</b> case sensitive!<br/>
<br/>

<b>2. </b>Now, if you only want to focus on certain columns from the 'machines' table, you can run the following query: SELECT A, B FROM machines;<br/>
  <br/>
    <img src="https://i.imgur.com/yXTqijU.png" height="80%" width="80%" alt="Columns"/>
<br/>
<br/>
<br/>

<b>3. </b>Let's check the OS Patch dates with that:<br/>
  <br/>
    <img src="https://i.imgur.com/Tor62bl.png" height="80%" width="80%" alt="OS Patch Dates"/><br/>
     <p>Note:<br/>Make sure to verify the directory has been added by running 'ls'<br/>
  <br/> 
  <br/>
  
<b>4. </b>Now, let's say we wanted to check the login activity.<br/>
 <br/>
    <img src="https://i.imgur.com/NUrgeOj.png" height="80%" width="80%" alt="Login Activity"/><br/>
       <p>Note:<br/>Make sure to verify the directory has been removed successfully by running 'ls'. We can see that 'temp' is no longer listed as well.<br/>
<br/>
<br/>
        
<b>5. </b>Now, check log_in_attempts:<br/>
 <br/>
    <img src="https://i.imgur.com/6OeKPXL.png" height="80%" width="80%" alt="Login Attempts"/><br/>
<br/>
<br/>

<b>6. </b>Let's organize this chart by 'login_date' so we can read it easier.<br/>
<br/>
    <img src="https://i.imgur.com/ZkH4vrg.png" height="80%" width="80%" alt="Organize by Login Dates"/><br/>
<br/>
<br/>

  <b>7. </b>Let's organize it again, by changing the 'Order by' login_date, and also login_time:<br/>
  <br/>
    <img src="https://i.imgur.com/soVfHzz.png" height="80%" width="80%" alt="Organize by login date and login time"/><br/>
<br/>
<br/>
<br/>
That's about it! We got a quick run down of how to Perform some SQL Queries with some simple 'Select' and 'From' and then also entering some table names! Thank you!
<br/>
<br/>
<br/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
