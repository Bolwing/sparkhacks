                                              SimplyCalendar - SparkHack 2023 UIC

Team Members:
Gor,
Kenneth,
Ahmad,
Vincenzo

<b>Project Description:</b> <br/>
SimplyCalendar is a Python application designed to help users easily import their class schedules from an HTML file and export class information.<br/> 
This includes the class name, day, and time and automatically exports it to the student's Google Calendar.<br/> 
While thinking of a project idea, we wanted to address our immediate community, our fellow students.<br/>
We decided to build this project to simplify the process of adding class schedules to calendar applications and save time for students by minimizing the complexity of exporting class schedules into Calendar.<br/>

<b>Key Features:</b> <br />
Automatically parses class information from HTML file<br/>
Extracts relevant class details, such as class name, day, and time<br/>
Exports class information in a format compatible with Google Calendar automatically<br/>
Streamlines the process of adding classes to a calendar<br/>

<b>Implementation Details:</b> <br />
SimplyCalendar is built using Python for parsing HTML files. <br/>
The program takes an HTML file as input, processes the file using the Google Calendar API to extract the required class information<br/>
It exports the class details automatically to the user’s Google account/email<br/>

<b>Usage Instructions:</b> <br />
Login on my.uic.edu -> XE Registration -> Register for classes -> Semester you want saved (e.g. Fall 23)<br/>
After the class schedule page loads, press the following keys: cmd + s and save your html file to a folder that contains the SimplyCalendar program<br/>
Run the program with your HTML file in the same directory<br/>
The program will output class information in a format compatible with Google Calendar<br/>

<b>Future Improvements:</b> <br />
Support for additional calendar applications<br/>
Automatic integration with calendar APIs for seamless import<br/>
Enhanced error handling and input validation<br/>
Support for extracting additional class information, such as location and instructor<br/>
Support images in addition to html file to export class information<br/>
