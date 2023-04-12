Python Input/Output (I/O):
---------------------------------------------

In Python, Input/Output (I/O) refers to the process of reading input
from external sources, such as the keyboard or a file, and writing
output to external destinations, such as the screen or a file.

Input in Python can be obtained using the built-in input() function,
which prompts the user to enter a value and returns it as a string.
For example:

name = input("Enter your name: ")
print("Hello, " + name)


Output in Python can be displayed on the screen using the print()
function. For example:

print("Hello, world!")


Python also supports file I/O operations. To open a file, you can
use the built-in open() function, which takes the file path and the
mode in which to open the file as arguments. For example:

file = open("example.txt", "r")


The mode argument can be "r" for reading, "w" for writing, or "a"
for appending to an existing file. Once a file is open, you can
read from it using the read() method or write to it using the
write() method. For example:

file.write("This is some text.")


Finally, it is important to close the file once you are finished
with it, using the close() method. For example:

file.close()

