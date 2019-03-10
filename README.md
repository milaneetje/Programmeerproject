# Programmeerproject

## Real world Problem 
When hosting a convention of some sort it is often hard to distribute information and gather registrations for example seminars. 

## Solution
A centralized app with a up to date interactive timetable where users can see all activities, find more information like location, time and a description, and register for activities.
![](images/Programmeerproject-idea.png)

## prerequisites
### Data sources
For this app I will use data from http://developer.perfectgym.com/api/overview/requests/ to get a number of different classes.
I will also use https://randomuser.me/ to create a bunch of fake users to create a fictional clientbase
### External components
I will use SQLite to create a database in which clients are entered, a database for every client to keep track of what classes they have registered for and a database for every class to keep track of which clients have registered for what class.
### similar apps
One application that GUI wise is how I'd envision my application would preferably look and work is the official application of the intreeweek of the UvA. https://play.google.com/store/apps/details?id=nl.intreeweek.app. I was not able to acces the sourcecode of this app so I can't be sure how they implemented different aspects of their application. 
### hardest parts
The SQLite functionality and getting data from the various API's might turn out to be more of a problem than I had previously figured. Front end wise I see that the time table might be a problem mostly due to the fact that I'd like to be able to scroll vertically as well as horizontally through the activity.
