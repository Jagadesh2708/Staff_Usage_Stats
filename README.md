# Staff_Usage_Stats
<h1>Generating a report to see the total number of staff in respective department</h1>


<h2>Description</h2>
This Power BI report is to give the total count of Staff in the department across all campuses of the University.
The purpose of this report to see the total staff in the respective department which can be used in the recruiting process and many other purposes.
<br />


<h2>Platforrm Used</h2>

- <b>SQL server Management Studio</b> 
- <b>Power BI</b>

<h2>Environment Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Report View: <br/>The visuals used in this report are:
<br/>Slicer - to categorise the Academic year,
<br/>Table - To show the list of columns used,
<br/>Stacked Column chart - To see the count of staff with respective Departments,
<br/>Card - To read the total count of Staff on the whole.<br />
<img src="https://i.imgur.com/TBa5z1f.jpg" height="80%" width="80%"/>
<br />
<br />
Source Code:  <br/>
The Staff details which includes their staff id's and names are taken from HR_Table.
<br/> Multiple joins(Inner and Left) are used to connect the Staff tables, department tables and Subject community tables<br />
<img src="https://i.imgur.com/gNHIg4G.jpg" height="80%" width="80%"/>
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
