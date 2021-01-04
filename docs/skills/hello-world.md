---
layout: default
parent: "Skills"
title: "Hello World"
nav_order: 4
has_children: false
--- 


# Hello World

A Python script can interact with you in one of two ways: printing text to the screen (also known as **The Console**) or interactively via you typing commands and it responding (also known as **The Command Line**).

(There are ***many*** other ways, in fact, e.g. controlling a user interface (e.g. like Windows), but these are much more complex.) 

Traditionally the first program everyone writes in a new language, editor or computer simply prints out the phrase `Hello World`. 

[Video demo](https://www.loom.com/share/472686db65a34dfb86b394b7ef5357e8)

In your editor open up a new file, type out the following and run it:

```python
print('Hello World')
```

Note that the various different parts of the code, the `print`, the brackets and their contents all show in different colours. This highlights that they all mean different things and that Thonny is helping you to make sense of it. 

## Printing to the screen 

In Python to print to the screen, you use the keyword `print` and then put the thing you want to print in brackets afterwards. 
The thing to print could be a number, some letters or a variable. 


Anything we print should be a string, but there's also the very useful comma, e.g. 

```python
a = 'Hello'
b = 3.14
c = 94
d = True
print(a,b,c,d)
```

This will print the contents of the variables `a`, `b`, `c` and `d` and print them out in turn all on the same line, each separated by a space.

Alternatively, 

```python
print(a)
print(b)
print(c)
print(d)
```

will print each variable on a different line. 

## Taking an Input 

The instruction

```python 
x = input("what is your word? ")
print("You said: ", x)
```

will print out the question "What is your word>", then wait for the user to type something (followed by Enter), then take whatever the user typed and put it in the variable `x`.

## A quick word about functions

We have already seen some functions, these are when you have a command word, followed by brackets which then have some values in them. The function has a name which needs to be unique and then there are arguments passed to the function. For example: 

```python
print("The print is a function, the string is the argument")
x = input("the input() function returns a string")
y = this_function_does_not_exist_yet() 
```

... and if you run that last instruction Python will complain. 

We will learn in due course about writing our own functions. 

# Next

More about [variables]({% link docs/skills/variables.md %}).

