A BRIEF OVERVIEW OF PYTHON IMPORT AND MODULES:

---------------------------------------------------------------
In Python, a module is a file containing Python definitions
and statements. The file name is the module name with the 
suffix .py appended. For example, a module named example
would be in a file called example.py. A module can contain
functions, classes, variables, and other modules.

Modules can be used to organize code into logical units and
to avoid naming conflicts. By using modules, you can break
your code into smaller, more manageable files, making it
easier to read, maintain, and reuse.

To use a module in your Python program, you need to import it.
The import statement is used to import a module into your code.
For example, to import the math module, you would use:

import math

Once the module is imported, you can use its functions, classes,
and variables by referring to them with the module name,
followed by a dot (.) and the name of the function, class, or
variable. For example, to use the 'sqrt()' function from the 'math'
module, you would write:

import math
x = math.sqrt(25)

You can also use an alias to refer to a module with a different
name. For example, to import the 'math' module with an alias of 'm',
you would use:

import math as m
x = m.sqrt(25)


There are other ways to import modules, such as importing specific
functions or classes from a module, but the basic syntax is the same:
'import module_name'.

