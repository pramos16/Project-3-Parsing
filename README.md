# Project-3-Parsing
Team members: Paola Ramos, Charles Smith 

## Problem
In order to solve the problem we have been give, we must compile the given data (email,login, date, time, etc.) and compile in into a report.
We must create a program that generates a report while also counting certain things such as irresponsible and suspicious behavior.

## Approach
For this project we created 4 different codes for each of the four tasks and placed them in a python notebook. 
To generate reports we used a variety of things such as loops, lists, counts, file handling, and conditional statements. 

Task #1: Suspicious Behavior 
This code consists of file handling and conditional statements. 
First we open and read the file we want. 
We then create a new textfile for the report that we would like. This textfile is the same as the sample given.
We use conditional statements to loop throught the text to locate the data we need.
In this case we needed to count the number of suspicious activity, so we used a counter. 
Functions such as line.strip() are used to remove either the beginning or trail of a string. 

Task #2: Irresponsible Behavior
This code consists of a lot of file handling and conditional statements. 
We began by opening the file and creating a new list to store it in and
Using conditional statements we loop through the data that allows us to repeat a block of code multiple times.
Phrases such as for line in ___ makes it easy to sort through each line and find what we're looking for which in this case is suspicious activity.
For this code we had to make sure to define multiple variables such as log in and log out using operators.
Condtional statements such as "If" and "Else" execute statements looking for whether the conditions satisfy the requirements and print a response. 

Task #3: System Glitch
This code is very similar to the code for task #2. The only thing is that we swtich log ins and log outs.
In this code we go through the same steps as before. 
We define our variables, log in and log out and loop through the file to search for the number of times each one occurs. 

In this code more log outs than log ins indicate a system glitch whereas in task #2 more log ins than log outs were irresponsible behavior. 



## Errors: 
Error 1:
One of the errors we had was with task #4. At first, we could only print a list of all the emails and counted the number of emails. The code also printed the first half of the email address instead of just the domain. To fix this we.. 

Error 2: A second error we had was with Task #3. We understood that all we had to do was do the opposite of taks #2. However, the code was not reporting glitches. 
To fix this error, at the bottom we switch Login > Logout with Logout > Login. 

Error 3: 


Error 3: 


## Flowcharts
 T
