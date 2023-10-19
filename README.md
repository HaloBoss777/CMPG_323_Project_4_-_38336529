<!DOCTYPE html>
<html>
<body>

<h1>CMPG_323_Project_4_-_38336529</h1>
<h1>Testing and RPA</h1>

<h2>Project Description</h2>
<p>Test the website for proper functionality using UIPath</p>

<h2>Project Manual</h2>
<p3>This test project is only made to be used on the website <a href="https://cmpg323-ecopowerlogistics.azurewebsites.net/">https://cmpg323-ecopowerlogistics.azurewebsites.net/</a> any other use of the project will result in unintended behavior</p3>
<p>The test can be run as a attended and unattended machine but there will be input required for the test to start</p>
<p>When the test is run through UIpath or UIpath assistant it will open new browser of chrome type and the user will need to input a email and a password to login or register on the site</p>
<p>Login:</p>
<img src="/Images/Login.png" alt="Login"></img>
<p>Register</p>
<img src="/Images/Register.png" alt="Register"></img>

<p>After the login or register you will be promted to choose a excel file to use as test data</p>
<img src="/Images/ChooseFile.png" alt="ChooseFile"></img>

<p>After the file is selected the test will use the sheets of the file to indecate which table of the database to test first</p>
<img src="/Images/Sheets.png" alt="Sheets"></img>

<p>As Customer is the first the test will go to the customer section of the website and test CRUD for every record in the customer sheet</p>
<img src="/Images/Customer.png" alt="Customer"></img>

<p>These steps will be followed for every record:</p>
<p>Step 1: Creates the record</p>
<img src="/Images/RecordCreate.png" alt="Create"></img>

<p>Step 2: The record will be tested to se if the data displayed is what was entered</p>
<img src="/Images/Read.png" alt="Read"></img>

<p>Step 3: The record will then be edited and compared to se if the edited data was saved and displayed</p>
<img src="/Images/Update.png" alt="Update"></img>

<p>Step 4: The record will be deleted after all the previos steps are completed</p>
<img src="/Images/Delete.png" alt="Delete"></img>

<p>After all the steps, the record is saved as TRUE if the test completed or FALSE if a error was encountered after steps repeat again until all records are tested in the current sheet</p>
<p>After a sheet is tested the test moves to the next table(Sheet)</p>

<p>After each sheet is tested and excel file is updated for each record the test is complete</p>

<h2>Website to use</h2>
<a href="https://cmpg323-ecopowerlogistics.azurewebsites.net/">https://cmpg323-ecopowerlogistics.azurewebsites.net/</a>

<h2>References:</h2>
<p>Lamb, B. 2023. UIPath Test Automation. https://www.udemy.com/course/uipath-test-automation/learn/lecture/19341046#overview Date of access: 10/15/2023</p>

<h2>Branches:</h2>
<p>Development and a main branch was used</p>

<h2>Link to Project</h2>
<a href="https://github.com/HaloBoss777/CMPG_323_Project_4_-_38336529">https://github.com/HaloBoss777/CMPG_323_Project_4_-_38336529</a>

</body>
</html>
