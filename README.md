HackAThonTest
=============
<h3>Route1:</h3>

<p>Master list. This master dictionary will be a page with all courses on it. <br />
If you are looking to sort classes but not use department as a factor, this page will come in handy. <br />
It’s probably useful for other reasons, too! <br />
<a href="http://course-api.herokuapp.com/master">Use the route:</a></p>


<h3>Route2:</h3>

<p>Use <a href="http://course-api.herokuapp.com/csci/">Department</a>, then <a href="http://course-api.herokuapp.com/csci/005/">course ID</a> (optional), then <a href="http://course-api.herokuapp.com/csci/005/01">section ID</a> (even more optional) to narrow selection to specific courses. <br />
Here's an example: <br />
’http://course-api.herokuapp.com/deptNameHere/ <br />
or <br />
’http://course-api.herokuapp.com/'dept'/'courseID'/'sectionsID' </p>


<h3>Basic Unit:</h3>

<p>The basic unit is “course” which will be listed as “MATH001” with the department listed first and the course number immediately following.</p>

<p>Each course has several attributes including: <br />
“start”        time; <br />
“end”          time; <br />
“status”       (open/closed/ “”); <br />
“instructor”   “Lastname, FirstInitial”; <br />
“bldg”         building abbreviation; <br />
“campus”       PZ/PO/CM/HM/SC; <br />
“days”         MTWRF; <br />
reg-limit”     “OpenSeats / TotalSeats.<br />   
“title”;      </p>


<p>To access this data, call <em>course[attributeHere]:</em></p>


