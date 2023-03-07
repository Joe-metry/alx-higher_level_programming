BRIEF EXPLANATION OF WHAT PYTHON IF/ELSE, LOOPS AND FUNCTIONS ARE:
-------------------------------------------------------------------

If/else
=======

Python if/else statements:

The if/else statement is used in Python to make decisions based on
certain conditions. The if statement evaluates a condition and
executes a block of code if the condition is true. The else statement
provides an alternative block of code to execute if the condition
is false. Here's an example:

x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")
-------------------------------------------------------------------
Loops
=====

Python loops:

Python has two types of loops: for and while loops. The for loop is
used to iterate over a sequence of values, such as a list or a string.
The while loop is used to repeatedly execute a block of code as long
as a condition is true. Here are some examples:

# for loop example
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# while loop example
x = 0
while x < 5:
    print(x)
    x += 1
-------------------------------------------------------------------
Functions
=========

Python functions:

A function is a block of code that performs a specific task.
It allows you to organize your code into reusable modules, making
it easier to read, debug, and maintain. In Python, you can define
a function using the "def" keyword. Here's an example:

def add_numbers(x, y):
    return x + y

result = add_numbers(3, 5)
print(result) # output: 8

