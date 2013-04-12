HackAThonTest
=============
<h2>Route1:</h2>

<p>Master list. This master dictionary will be a page with all courses on it. <br />
If you are looking to sort classes but not use department as a factor, this page will come in handy. <br />
It’s probably useful for other reasons, too! <br />
<a href="http://course-api.herokuapp.com/master">Use the route:</a></p>


<h2>Route2:</h2>

<p>Use <a href="http://course-api.herokuapp.com/csci/">Department</a>, then <a href="http://course-api.herokuapp.com/csci/005/">course ID</a> (optional), then <a href="http://course-api.herokuapp.com/csci/005/01">section ID</a> (even more optional) to narrow selection to specific courses. <br />
Here's an example: <br />
’http://course-api.herokuapp.com/dept_name_here/ <br />
or <br />
’http://course-api.herokuapp.com/<dept>/<course_id>/<sections_id> </p>


<h2>Basic Unit:</h2>

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


<p>To access this data, call ’course[<attributeHere>]:</p>




Basic Unit: 
The basic unit is “course” which will be listed as “MATH001” with the department listed first and the course number immediately following.

Each course has several attributes including: 
“start” time; 
“end” time; 
“status” (open/closed/ “”); 
“instructor” “Lastname, FirstInitial”; 
“bldg” building abbreviation; 
“campus” PZ/PO/CM/HM/SC; 
“days” MTWRF; 
“title”;
“reg-limit” “OpenSeats / TotalSeats.

To access this data, call course[‘attributeHere’]:




Route1: Master list. This master dictionary will be a page with all courses on it. If you are looking to sort classes but not use department as a factor, this page will come in handy. It’s probably useful for other reasons, too! Use the route: http://course-api.herokuapp.com/master

Route2: Use Department [HYPERLINK] , then course ID [HYPERLINK] (optional), then section ID [HYPERLINK] (even more optional) to narrow selection to specific courses. 

