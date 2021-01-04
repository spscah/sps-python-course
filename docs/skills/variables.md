---
layout: default
parent: "Skills"
title: "Variables and Data Types"
nav_order: 8
has_children: false
--- 

# Variables 

Variables can simply be thought of as boxes which we can use to hold a value. We can **assign** a value to a variable, i.e. put a thing into the box. This is done using the equals sign, `=`. The variable goes on the left and the thing to put in it on the right. 

```python
x = 1 
```

This would put the value `1` in the variable called `x`. 

Then, whenever we use the value `x` Python will use the number `1` instead. 

.Variable must begin with a letter (either case) and then letters or an underscore (but no spaces). 

**Video**: [naming variable](https://www.loom.com/share/98d4a44259194088896a50a09b515be3).

The thing in the box can be of a number of built in types. While we don't have to tell Python what type a particular variable is, which type it is will determine what we can do with it. 


# Data Types

Every variable has a type (although that type can change). To begin with there are four types we're interested in: strings, integers, floats and booleans. 

**Video**: [playing with types](https://www.loom.com/share/8435483e5f6e4508bd26f49d563f8bc8)


## String

A string is any collection of characters and symbols, in Python this is indicated by using either single quotes `'` or double quotes `"` to mark each end of the string. 

```python
s1 = 'string using single quotes' 
s2 = "string using double quotes" 
```

We can join two strings together using the `+` symbol. 

We can copy the string a number of times using the `*` symbol. 

e.g. 

```python
print(s1 + s2)
```

or

```python
h = 'hello'
i = h * 3
print(i)
```


## Boolean 

The boolean type (often spelt with a capital B after its inventor [George Boole](https://en.wikipedia.org/wiki/George_Boole)) contains just one of two values: **true** or **false**. In python these are capitalised, e.g. 

```python
b1 = True
b2 = False 

print(b1, b2)
```

Although these are words, they are not strings. You will note that in your python code they change colour (change to a lower case first letter to spot the difference).

Boolean variables are often used to store the state (i.e. the current situation) of something, for example that something hasn't happened (the user hasn't inputted the correct answer) or that we're still waiting for something (the user hasn't pressed a key). 

### Comparisons

Booleans are often used to store the result of comparisons: e.g. that one variable is bigger than another, or that two variables do not contain the same values. 

We can use familiar operators, like `>` or `<` to see if values are bigger or smaller (or `>=` or `<=` to check for equality too). 

Then there's `==` to check if two values are the same. Note the difference between `==` to compare two values as opposed to `=` that's assigns the right hand side to the variable on the left hand side. 

**Video**: [comparing two values to create a Boolean variable](https://www.loom.com/share/2eaff8d080634d1ab40090583f3f5da2).

One very interesting comparison you can make is to check if a variable is between two others, e.g. checking if a score is between 0 and 100: 

```python
score = 65

if 0 <= score <= 100:
	print("that's a valid score")
else: 
	print("that doesn't look right")
```

This allows us to check that a score is both greater than or equal to the lower limit and less than or equal to the higher limit. 

**Video**: [checking a variable is between two limits](https://www.loom.com/share/ed351e3b06c74c40901f06722f74546c).

## Integer

E.g. division, integer division, mod, divmod 

**Video** [Introduction to integers](https://www.loom.com/share/81a509dc34944fbdb91fb0ae21f5f68f)


### Dividing by negatives 


## Floats 

A number with decimal places is called a float. 


# Arithmetic 

[Multiplication needs to be explicit](https://www.loom.com/share/4e3c09be07624ac8b80c00f08cb1f2ec), unlike in maths. 

# Updating Variables 




