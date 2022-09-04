# 4533FoxFarm

GENERAL DESCRIPTION
This code to create a private home automation web portal with data and connectivity to a select group of home automation devices.   What is published in github so far is just a starting point of taking a personal project, uploading it publically, practicing with GIT more, and working on cleaning the codebase to something more fit for public consumption.

CAN YOU USE THIS?
Yes and no.  Within the licening you can pretty much do what you want with this code (see license.md).   Will it help you?  So far only if you're proficient in taking snippets of code to do specific things e.g. toggle a .jpg image on a webpage based on DC voltage input on a pin on a Raspberry Pi.

A LITTLE BIT MORE
This is a personal project where I have a PHP website showing the status of my garage door opener, sump pump, electical supple to home, security cameras, thermostat, key devices on my home network, a calendar, and a customized display of weather.  The garage door opener and thermostat can be controlled via the website.  The sump pump and electrical supply to home monitors and calenader send both text and email alerts to multiple recipients.  Some monitors such as the sump pump or electrical supply to home monitors require custom wiring of a Raspberry Pi (or other device) which can tigger the code or provide data to the code.  The custom weather display is currently using the Dark Sky API, however that appears to be shutting down as it's been sold to Apple (I think). 

IMMEDIATE PROJECT GOALS:
1.) Get code into GIT/Github.   Figure out how to upload current code, but not private information like usernames, password, IPs, hostnames, etc.
2.) Clean up code and get a clean commit process from local codebase to github
3.) Test downloading codebase to alternate location to keep home location working as normal. 
4.) Figure out if going with multiple prod, dev, test environments or update from prod only and rely on GIT for versioning.
5.) Assess where current weather API usage is at and if moving to Apple's is a feasible thing or not.
6.) The API for google maps commute times in the wearther display is dead.  Investigate.
7.) The API / functionality of displaying weather for not my home address or searching for other cities to see their weather display is no longer working.  Fix.


OVERALL LONGER TERM GOAL:
1.) Make this software something that some could download, run some instalers, get some database created, etc and actually use this software in a more out of the box fashion.
2.) Mechanism for allowing a user of the software to create an interface to their own smart device, Rasperberri pi/Arduino output, etc and display on this sites dashboard.
3.) Make it look pretty
4.) Come up with list of actual requirements, down to the versions, etc on what you need to run this if it were an actual project people could download and use.
