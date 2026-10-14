# Overview 
Command-line program that allows a user to scan the ports on their device using an IP address. The program outputs whether the port(s) chosen are open or closed, and depending on the option chosen, prints the number of closed and open ports.

# Features
- Single port scan - program scans single port.
- Multiple port scan - scans multiple ports entered by user.
- Common port scan - scans from a list of common ports defined at the start of the program. These also provide the service name.
- Output summaries - prints out summaries including if the port(s) is open or closed, and how many ports are open/closed.
- Service identification - the constants defined allows services to be printed alongside some port numbers, such as 25 or 80.
- Error handling - provides specific error messages.
- Specific date/time - prints the date and time that the scan started / ended.

# Tech stack
- Python
- Socket ('import socket')
- Sys ('import sys')
- Datetime ('from datetime import datetime')
