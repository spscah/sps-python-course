---
layout: default
parent: "Skills"
title: "Running Python"
nav_order: 2
has_children: false
--- 


We use Python 3 (officially it's up to version 3.8 but for our sakes, any version 3.x will be fine). On this page we look at one way of running Python on your machine. There are [other ways]({% link docs/skills/running-python-2.md %}).  


--- 

# Desktop (Mac, Windows, Linux)

On a 'normal' computer you will be running a full app (known as an IDE, an *Integrated Development Environment*) to write your Python code. We suggest that you start with an app called Thonny. After that, you might move on to other editors (e.g. IDLE or PyCharm).   

## Thonny

Thonny is a friendly application for running your Python code. You can download it at [thonny.org](https://thonny.org/) and is available for Windows, Mac or Linux. 

A video outlining [the first steps in Thonny](https://www.loom.com/share/9e0b905de7bb4cf0a8d82b77b17d98ee). 

## Debugging 

In the Thonny editor you can select (*View* > *Variables*) to show a window with all the variables in your script. 

Press the 'bug' symbol to walk through your code, line-by-line. 

As you step through, the variables tab will show the current state of all the variables. 

**Video**: [debugging with Thonny](https://www.loom.com/share/a4286caabade42f79c42acb47d446d77).

- Step over: execute the current statement, quickly resolving all the variables and call the function, move to the next line 
- Step into: resolve each and every part of the line in turn, showing how they call underlying processes and then have the results be joined together 
- Step out: move to the next layer up (i.e. if in a step out), or if in a function, move out to the place where the function was called 

# Next

Move on to [`Hello World`]({% link docs/skills/hello-world.md %}).
