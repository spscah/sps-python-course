---
layout: default
parent: "Skills"
title: "Taking Decisions"
nav_order: 20
has_children: false
--- 

# Taking Decisions

Previously we saw how we can use [comparisons to set Boolean variables]({% link docs/skills/variables.md %}). 

We can use those comparisons (or their Boolean variable) to control which lines of the Python code get run and which don't. 


## if .. else 

Often we will have a straight choice between two options, if something is the case we do one thing, otherwise we do a second thing. In spoken English this would be "if some condition holds do this, otherwise do that". 

"If it is raining put on my coat, otherwise wear a t-shirt."

In Python we do this using the keywords `if` and `else`.

I have asked someone their age and I want to check if they're old enough and then to print a suitable message, e.g. 

```python
age = int(input("What is your age? "))
if age >= 18: 
	print("You're old enough.")
else: 
	print("You're not old enough.")
```

There are several things to note here: 

- the space after the `if`
- the condition is something that returns a Boolean, so it could be a Boolean variable or, like here, some comparison that returns a Boolean
- the colon after the condition 
- the indentation of the line after the `if` statement 
- the colon after the `else` and the indentation after that line 

The lines following the equals (whether on the `if` or the `else` lines) are called *blocks*. You can have several lines in block, so long as they are all indented the same amount. 

**Video**: using [if ... else ... ](https://www.loom.com/share/489690be3b834927982cb81bc4b57846) to make a direct choice. 

### if

You don't have to have an else. 


## if ... elif ... else ... 

If you must choose one option between several choices, you should use `elif`, e.g. a pass mark is 50, but if you score 90 you get a distinction; but if you get a distinction you don't get a pass as well, so we should only get one message. We could do it like this: 

```python
score = 50 

if score > 90: 
	print("distinction")
if score > 50: 
	if score < 90: 
		print("pass")
if score < 50:
	print("fail")
```

but this requires us to use an `and` clause to combine `if` statements or, like here, embedding several layers of `if` which gets confusing and makes us liable to make mistakes. 

Far neater is to narrow down our options like this: 

```python 
if score > 90: 
	print("distinction")
elif score > 50: 
	print("pass")
else: 
	print("fail")
```

This works by making the first check, if it's true, go into that branch if it's false try the next check. 

**Note:** Each `elif` needs a separate condition. The `else` never takes a condition. 


- [if/elif/else](https://www.loom.com/share/08fd93e1c4e247eb852a18147bb2a7b4)
