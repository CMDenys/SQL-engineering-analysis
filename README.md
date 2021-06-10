<p align="center">
  <img src="images/0.1_cover.png" width="400"/>
</p>

In this research project data modeling, engineering, and analyis were peformed on employees of a corporation from the 1980s and 1990s. All that remain of the database of employees from that period were six CSV files.
<br>
<hr>
<br>

<p> <img src="EmployeeSQL/sql_challenge_ERD.png" align="right" width="500"/>
<h4>Data Modeling</h4>
The first step was to inspect the CSV's, design tables, and sketch them out in an ERD.  To facilitate this first step, Quick-DBD was used.
</p>
<br clear="right"/>
<br><br>

<p>
<h4>Data Engineering</h4>
Next, the information used to create the ERD was used to build a table schema for each of the six CSV files. In this step, data types, primary keys, foreign keys, and other constraints were identified.
</p>
<br>
<p align="center" float="left"> 
  <img src="images/1_table_1.png"  width="400"/>
  <img src="images/2_table_2.png" width="400"/>
</p>
<p align="center">
<img src="images/3_tableKeys.png" width="600"/>
</p>
<br>

<p> <img src="images/4_dataPull.png" align="right" width="250"/>
<h4>Data Analysis</h4>
Finally, the CSV's were imported into a SQL database (PostgreSQL) where schema queries were run to answer questions about the data.  
</p>
<br clear="right"/>
<br>

<p>
<h3>Below are the individual schema queries that were run once the individual data sets were combined.</h3>
</p>
<hr>
<br>
<p> <img src="images/5_emplDetails.png" align="right" width="500"/>
  <strong>List of details for each employee:</strong>
<ul>
  <li>Employee Number</li>
  <li>Last Name</li>
  <li>First Name</li>
  <li>Sex</li>
  <li>Salary</li>
</ul>
</p>
<br clear="right"/>
<br><br>
 
<p> <img src="images/6_hireDate.png" align="right" width="500"/>
  <strong>Employees hired in 1986:</strong>
<ul>
  <li>First Name</li>
  <li>Last Name</li>
  <li>Hire Date</li>
</ul>
</p>
<br clear="right"/>
<br><br>

<p> <img src="images/7_deptMan.png" align="right" width="500"/>
  <strong>The manager of each department with the following details:</strong>
<ul>
  <li>Department Number</li>
  <li>Department Name</li>
  <li>Manager's Employee Number</li>
  <li>Last Name</li>
  <li>First Name</li>
</ul>
</p>
<br clear="right"/>
<br><br>

<p> <img src="images/8_deptEmp.png" align="right" width="500"/>
  <strong>The department of each employee with the following details:</strong>
<ul>
  <li>Employee Number</li>
  <li>Last Name</li>
  <li>First Name</li>
  <li>Department Name</li>
</ul>
</p>
<br clear="right"/>
<br><br>

<p> <img src="images/9_hercules.png" align="right" width="500"/>
  <strong>Details for employees whose first name is "Hercules" and last names begin with "B":</strong>
<ul>
  <li>First Name</li>
  <li>Last Name</li>
  <li>Sex</li>
</ul>
</p>
<br clear="right"/>
<br><br>
 
<p> <img src="images/10_empSales.png" align="right" width="500"/>
  <strong>List of all employees in the Sales department, including the following details:</strong>
<ul>
  <li>Employee Number</li>
  <li>Last Name</li>
  <li>First Name</li>
  <li>Department Name</li>
</ul>
</p>
<br clear="right"/>
<br><br>

<p> <img src="images/11_salesDev.png" align="right" width="500"/>
  <strong>List of all employees in the Sales and Development departments, including the following details:</strong>
<ul>
  <li>Employee Number</li>
  <li>Last Name</li>
  <li>First Name</li>
  <li>Department Name</li>
</ul>
</p>
<br clear="right"/>
<br><br>
  
<p> <img src="images/12_nameCount.png" align="right" width="500"/>
  <strong>In descending order, a list of the frequency count of employee last names, i.e., how many employees share each last name</strong>
</p>
<br clear="right"/>
<br><br>
  


