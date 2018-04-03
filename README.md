# Week-7-Lab-CodePath
Week 7 Lab Project
WEEK 7 LAB ~ WORDPRESS VULNERABILITIES


Vulnerability 1:

User Enumeration, WordPress version 4.2

After attempting multiple logins, we noticed that the first login attempt returns invalid username. Next we tried admin and were prompted with a warning saying “The password you entered for the username Admin is incorrect.” This vulnerability demonstrates that a user can sufficiently determine a correct username and potentially brute force a password.




Vulnerability 2:

XSS, CVE-2016-7168, Test Version: WordPress 4.2, patched WordPress 4.6.1:

We found a XSS bug that allows a script to be executed in the comments section of a post. A simple script was inserted and enabled a pop up window to appear.



Vulnerability 3:

XSS, CVE-2017-9061, Test Version: WordPress 4.2, patched WordPress 4.7.5:

We found another XSS vulnerability that inserted java script. The script is executed by the browser because of an error message. This message gets generated, interpreted, and executed as a script originating from the webserver. 


