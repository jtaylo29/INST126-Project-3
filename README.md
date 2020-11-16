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

# Updates
- My first plans for writing the code were way to simplistic and that was due to me not fully understanding what I needed to do and how to actually to it properly. i had to go back and review class recordings and use other resources like the Python for Everybody text and stack overflow.
- My first code for all four reports is very confusing and had too many loops and conditional statements that were not needed for the code to run or for the reports to generate properly. I need to find a different way to write the code without it getting too long and confusing.
- I was able to write a simpler 
   
# Errors
1. 
2. I couldnt get the domain_count file to write at first, which I then realized it was because the domain count required its own separate write file code. Even then when I wrote the code for the domain file, it wouldn't generate the file with the correct format. Since no error message was given I had a hard time figuring out what I was missing. After reviewing it many times, I realized I needed to add "len" after "str" for the domain_dict. 
  
