# NEOGRID

## SETUP
Download the file and run.

Problem Statement - Conference Track Management

You are planning a big programming conference and have received many proposals which have passed the initial screen process but you're having trouble fitting them into the time constraints of the day -- there are so many possibilities! So you write a program to do it for you.

· Don't use plugins utilities for date calculate: Joda-Time
· Use input data: input.txt - you should use this file for input data on system
· The conference has multiple tracks each of which has a morning and afternoon session.
· Each session contains multiple talks.
· Morning sessions begin at 9am and must finish by 12 noon, for lunch.
· Afternoon sessions begin at 1pm and must finish in time for the networking event.
· The networking event can start no earlier than 4:00 and no later than 5:00.
· No talk title has numbers in it.
· All talk lengths are either in minutes (not hours) or lightning (5 minutes).
· Presenters will be very punctual; there needs to be no gap between sessions.

Note that depending on how you choose to complete this problem, your solution may give a different ordering or combination of talks into tracks. This is acceptable; you don’t need to exactly duplicate the sample output given here.

Test input :-
------------

Writing Fast Tests Against Enterprise Rails 60min
Overdoing it in Python 45min
Lua for the Masses 30min
Ruby Errors from Mismatched Gem Versions 45min
Common Ruby Errors 45min
Rails for Python Developers lightning
Communicating Over Distance 60min
Accounting-Driven Development 45min
Woah 30min
Sit Down and Write 30min
Pair Programming vs Noise 45min
Rails Magic 60min
Ruby on Rails: Why We Should Move On 60min
Clojure Ate Scala (on my project) 45min
Programming in the Boondocks of Seattle 30min
Ruby vs. Clojure for Back-End Development 30min
Ruby on Rails Legacy App Maintenance 60min
A World Without HackerNews 30min
User Interface CSS in Rails Apps 30min

Logic :-
------------

First of all extract the txt file separating the text as title and the number being time in minutes.

I delimited the conferences by groups from 9:00 am to 12:00 and from 13:00 until networking that would be between 4:00 p.m and 5:00 p.m.

Remembering the exception for lightning.
