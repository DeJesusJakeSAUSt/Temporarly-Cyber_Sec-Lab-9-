# Temporarly-Cyber_Sec-Lab-9-
Red, Blue, and Green Targets were the assignment for this week's project. Thank you

See branches for assignments

# Pen Testing Live Targets

Time spent: **3** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: _My SQL Injection_________________

Description: This is for the Blue Target assignment. Basically, for the blue target, I clicked on User Salesmen and on the first guy, I noticed it using IDOR because of the ID parameter. Therefore, I erased the id parameter number and replaced it with a sql method of injection using 'OR'1'='1 and still it redirected me to the first guy as if it was id=1.

<img src="Blue target snip.gif">


## Green

Vulnerability #1: ___User Enumeration Attack_______________

Description: This one is for the Green Target assignment. Basically, I clicked on the Log In page and once it directed me to the login in screen, I inputted the username "pearson" for CTF challenge creditenals, but used a random password instead of the real one. Afterward, I got an error message about the log in info, but it was bolded instead of not. This represents a vulnerability in the usernames of the database for this target. 

<img src="Green Target.gif">


## Red

Vulnerability #1: ____IDOR Vulnerability______________

Description: This one is for Red Target assignment. For this one, the same with the Blue Target with me having to replace the ID parameter with new input, but only this time I used numbers 1-11 and for 1-9, it displays all of the salesmen names correspondily, but for targets 10 and 11, they display a restricted zone page not authorized for regular viewers. I took a snip of number 11 as the ID parameter and it displayed the vulnerabilty of me gaining unauthorized access to the restricted site and being fired for stealing.

<img src="Red Target snip.gif">


## Notes I believe and hope we only need to find at least 1 vulnerability in 3 targets/

Describe any challenges encountered while doing the work
This was not too much of a challenge unlike Lab 8 but I still think I have trouble setting up GIF files for submission. 
