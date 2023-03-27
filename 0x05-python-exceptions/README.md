An Overview of Exceptions in Python:
-----------------------------------

In Python, exceptions are events that occur during the execution
of a program that disrupt the normal flow of the program's
instructions. When an exception occurs, Python stops executing
the current function and jumps to the nearest exception handler.

To handle exceptions in Python, you can use try-except blocks.
The basic syntax is:

try:
    # code that might raise an exception
except ExceptionType:
    # code to handle the exception
=================================================================

In this example, ExceptionType is the type of exception you want
to catch. If an exception of that type is raised in the try block,
Python jumps to the except block to handle the exception.

You can also have multiple except blocks to handle different
types of exceptions, or you can have a generic except block
that catches all exceptions:

try:
    # code that might raise an exception
except TypeError:
    # code to handle TypeError
except ValueError:
    # code to handle ValueError
except:
    # code to handle any other exception
==================================================================

In addition to try-except blocks, you can also use try-finally
blocks to ensure that some code is always executed, regardless of
whether an exception is raised or not:

try:
    # code that might raise an exception
finally:
    # code that is always executed
==================================================================

Finally, you can also raise exceptions yourself
using the raise statement:

raise ExceptionType("Error message")


This raises an exception of type ExceptionType
with an optional error message.

