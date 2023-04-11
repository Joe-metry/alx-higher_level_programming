brief on Python - Inheritance:
------------------------------

Inheritance is a fundamental concept in object-oriented programming (OOP)
that allows a class to inherit properties and methods from another class.
In Python, inheritance is implemented using the class keyword and the name
of the parent class in parentheses after the name of the child class[1][2][3].
Here's an example of a simple inheritance hierarchy in Python:

class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        raise NotImplementedError("Subclass must implement abstract method")

class Dog(Animal):
    def speak(self):
        return "Woof!"

class Cat(Animal):
    def speak(self):
        return "Meow!"

dog = Dog("Fido")
cat = Cat("Whiskers")

print(dog.name + ": " + dog.speak())
print(cat.name + ": " + cat.speak())


In this example, we define a parent class Animal with an abstract method speak().
We then define two child classes Dog and Cat that inherit from Animal and implement
their own versions of speak(). Finally, we create instances of Dog and Cat and call
their speak() methods.
When a child class inherits from a parent class, it inherits all the properties and
methods of the parent class. The child class can then override or extend the behavior
of the parent class by defining its own properties and methods
