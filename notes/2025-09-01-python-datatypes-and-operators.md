* Course/Module/Topic: Udacity Introduction to Python  
Lesson: Data Types and Operators  
Date: 2025-09-01  
Type: note  
Tags: Python, basics, Data Types, Operators  
Related Project(s)  
Related journals: [2025-09-04 Pyhon Data Types and Operations](https://github.com/NikiDigitals/Computing-IT/tree/main/journals/2025-09-01-python-datatypes-and-operators.md)
---------------

## Overview
How to use different operators and how to use them for calculations.
How to use and name variables correctly in Python.
The different assignment operators.

## key concepts
* Operators: The use of operators in Python: PEMDAS: Parentheses, Exponents, Multiplication/Division, Addition/Subtraction.
* Variable: You can assign a variable to a value, which will then store the value. After that, you can change the value inside the variable.  
* When naming a variable, there are some rules in Python:
1. Only use ordinary letters, numbers and underscores in your variable names.
2. You can’t use reserved words or built-in identifiers as a variable name
3. When naming, use all lowercase letters and underscores to separate words. This is called snake case.

## Definitions/Syntax
<b> print() </b> is a built-in function that displays input values as text in the output.

<b>Arithmetic operators:</b>  

" + " addition  
" - " subtraction     
" * " multiplication     
" / " division  
" % " mod (the remainder after dividing)  
" ** " Exponentiation   
" // "  Divides and rounds down to the nearest integer

 <b>Assignment operators:</b>  
 " = "  x = 2   
 " +="  x = x + 2  
 " -= " x = x - 2  
 " *= " x = x * 2

## Examples
Use the print()
```python
print("Hello World")
```
Use the operators:

``` python
x = 5 + 3
print(x)
```

Use of variables and assignment operators:

```python
rainfall = 5e6                 # The amount of rainfall (in cubic metres)
reservoir_volume = 4.445e8     # The current volume of a water reservoir (in cubic metres)
rainfall *= .9                 # decrease the rainfall variable by 10% 
reservoir_volume += rainfall   # add the rainfall variable to the reservoir_volume variable
reservoir_volume *= 1.05       # increase reservoir_volume by 5% 
reservoir_volume *= .95        # decrease reservoir_volume by 5% 
reservoir_volume -= 2.5e5      # substract 2.5e5 cubic metres from reservoir_volume 
```

## lesson learned
- Learned how to use the operators and make simple calculations using Python.
- LEarned how to assign a variable name to a value and how to change the value of that variable. 

## external resources: 
[bitwise operators](https://wiki.python.org/moin/BitwiseOperators)   
[order of operations in Math](https://en.wikipedia.org/wiki/Order_of_operations)   
[Python reserved words](https://docs.python.org/3/reference/lexical_analysis.html#keywords)

