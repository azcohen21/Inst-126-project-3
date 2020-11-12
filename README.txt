group members

1. Alex Cohen
To use the program, run the cell block and see the text files of the reports.

Update 11/11/20: 
  
  I have combined all of the individual programs into one cell to run only once. It will generate all of the text files. 
  The logic of the programs has largely remained the same since the creation of the flowcharts. If you look at my original flowcharts, you will see that there are decision blocks for questions that would end up being done automatically by the for loops in the code. I have removed any instance of the questions as they don't need to be coded in except as for loops. 
  Formatting for the text files has been done to copy exactly the example reports from class. This was done by using tab spaces and line breaks. Due to the usage of the write function, I have had to include extra linebreaks at the end of any line that started with "print(" as write does not automatically include the line breaks.
  The code now detects if event[2] (log status) is "login" or "logout", and it indents all instances of event[3] (server name) if event[2] is "logout", like the example report.
  For suspicious activity, I added funcitonality for detecting if a login was early by setting early logins to be true if the login hour was 5 or less.
  
11/2/2020 I have uploaded flowcharts and have added code to open and read the userlog.log file
  The flowcharts are pretty straightforward, and show the basic logic for the functions that will be created for the program to interpret the log.
  I will be using dictionaries within dictionaries (nested dictionaries) to store different parts of the data from the log sheet and to store results from the respective functions.

here is a basic idea of what my refrences to the data will look like:
 “User2”: {“2020-05-23”: [event date, time, log status, server, email] } }
 
