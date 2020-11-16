# INST126-Project-3

Group 27 - Jacqueline Taylor

For project 3, we will be simulating a professional working environment where most of the software and digital activities are recorded using log files. In this project I will have to analyze and generate reports for four areas including suspicious activities, irresponsible behavior, system glitch and domain count. There are a total of 50 users with a log file generated over the month of May 2020. The reports I make will aid in making decisions for the higher officials.  

# Problem Statement and Tasks

1. Suspicious Behavior
Report the total count of suspicious activities. Suspicious behavior is marked if a user has logged into the system more than 5 times in a single day, or if the user has logged into the system anytime between 12:00 am to 5:00 am. 

2. Irresponsible Behavior
Report the total count of irresponsible behaviors. Irresponsible behavior is marked if a user does not logout after logging in, this is checked by seeing if a user has more logins than logouts.

3. System Glitch
Report the total count of system glitches. A system glitch is marked when the sytem records more logouts than logins for any user. 

4. Domain Count
Report a list of all the domains and the number of users within each domain.

# Updates
- My first plans and flowcharts for writing the code were way to simplistic and that was due to me not fully understanding what I needed to do and how to do it properly. I went back and reviewed class recordings and exercises and I used other resources like the Python for Everybody text and stack overflow.
- I made changes to and created new flowcharts (see flowcharts folder). My first flowcharts were too simple and didn't provide enough information to help me build the code, it more so gave me a vague outline. Although no major changes were made, for each insight I added specific lines of code in the boxes to help me organize the flow of the task.
- My first code for all four reports is very confusing and has too many loops and conditional statements that are not needed for the code to run or for the reports to generate properly. I need to find a different way to write the code without it getting too long and confusing.
- I was able to write a simpler code that I was able to understand. I encountered fewer errors once I shortened my codes and it made more sense to me.
- To generate the report files I started out by writing the create_file code for each insight which was tedious and made the overall code longer. I made the decision to have only one write code that would work in generating reports for suspicious activities, irresponsible behaviors, and system glitches. Then, at the end I could generate all of the reports at once in a separate cell.
   
# Errors
1. I first tried using the define function for each insight but whatever I tried I kept getting an NameError saying my function was not defined. I opted out of defining the insights and instead just went straight into defining a dictionary for each insight. For one it would actually run with no errors, and two it helped with writing my code for efficiently.
2. I couldn't get the domain_count file to write at first, which I then realized it was because the domain count required its own separate write file code. Even then when I wrote the code for the domain file, it wouldn't generate the file with the correct format. Since no error message was given I had a hard time figuring out what I was missing. After reviewing it many times, I realized I needed to add "len" after "str" for the domain_dict. 
3. I didn't realize until after the reports were written that they were in the wrong format. It took a bit of reviewing to find out what in the code I needed to change or add in order for the report to be formatted properly. There were a couple of errors in the file reading cell that caused the formatting and lines to be off.
