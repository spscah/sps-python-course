---
layout: default
parent: "Skills"
grand_parent: "Python"
title: "Converting between types"
nav_order: 10
has_children: false
--- 


# Converting to integers 

## String to integer 

The Python command `x = input()` returns a string. We can tell that it's a string by looking into the Variables tab on Thonny and see that its value is shown using single quotes. 

We can't use that value directly as an integer, though. 

We need to use the command, `int()`, e.g. 

```python 
st = '123'
i = int(st)
``` 

So long as the thing inside the string variable is a whole number, the `int()` function will return the value as an integer. 

**Video**: [Converting strings into integers](https://www.loom.com/share/9ef5803c518f42cfa165604951abe6f2).

## Float to integer 

A float value, i.e. a number with a decimal point, can be used to return an integer value using the `int()` function too. It will truncate any decimal points, e.g. 

```python
f1 = 3.14
i1 = int(f1)
f2 = 3.9
i2 = int(f2)
f3 = -3.14
i3 = int(f3)
f4 = -3.9
i4 = int(f4)
```

You can use the difference between the two values to work out the amount truncted, e.g. 

```python
d1 = f1 - i1 
``` 

**Video**: [Converting floats to integers](https://www.loom.com/share/26dda4853c4e47b69c12540454cf7891).

# Converting to strings 