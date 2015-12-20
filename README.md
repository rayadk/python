# About this collection
This is a collection of Python projects I did for a couple classes I took on Coursera: "An Introduction to Interactive Programming in Python." This was my first foray into Python and it was awesome! All the assignments were games so it created a natural incentive to work on them _and_ do lots of testing :)

In the script for each game, you can find a high-level description at the top and inline comments that give all the gory implementation details, if you're into that kinda thing.

# Running the games
To run any of the games, click on their corresponding links and hit the play button:

```Rock-paper-scissors-lizard-Spock``` - http://www.codeskulptor.org/#user40_JKfBKeao2bS4V4u.py

```Guess the number``` - http://www.codeskulptor.org/#user40_mDuf489chVFU2Ql.py

```Stopwatch: The Game``` - http://www.codeskulptor.org/#user40_DF6KaiYG369DqUt.py

```Pong``` - http://www.codeskulptor.org/#user40_ddTD4BZHw5IvRt3.py

```Memory``` - http://www.codeskulptor.org/#user40_WUzHfB2xjzexdmk.py

```BlackJack``` - http://www.codeskulptor.org/#user40_tPDKdciBwjqzdOW.py

```Asteriods``` - http://www.codeskulptor.org/#user40_0jA71tbX3ZEmTSy.py

You don't have to install anything but you must have Javascript enabled and allow pop-up windows. Chrome is highly recommended (required for Asteriods!) but Firefox and Safari will also do.  Do not use Internet Explorer, ever. Since some games require keyboard and mouse input, you'll want to run them on an appropriate platform.

Note: If there's a problem with any of the links, just copy and paste the code directly into CodeSkulptor and hit play to run it.

# Technical points
The class used CodeSkulptor (http://www.codeskulptor.org/), a web-based Python development environment that implements a subset of Python 2, as a platform for writing and submitting assignments. My scripts were written there and take advantage of the platform's built-in functionality, particularly its _simplegui_ library.

The games start off as console-based and quickly transition to being fully GUI-based. In this process, they move from being functional to object-oriented to event-driven which makes use of input fields, buttons, and timers. They also leverage keyboard and mouse input. Data structures, particularly lists and tuples, dictionaries and sets, are heavily used in the later games.
