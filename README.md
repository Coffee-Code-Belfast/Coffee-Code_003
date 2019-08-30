# Coffee&amp;Code#003: Python and Flask 
### Created by Ciara Magee
### Guest mentor David Cutting

# Today’s Challenge:

We will be discovering Python and practicing with exercises. if you have time, there is also an option to create a simple web app using a Flask server.

If you are are completely new to any programming language, check out this post on dev.to by Ali Spittel: A Complete Beginner's Guide to Programming. There are also more resources to read at the end of this doc, which you can do here or in your own time! If you’d like to go ahead and try writing some Python code, either by pairing up with someone or on your own, please go to the Set Up section below then on to Python Exercises on the next page.

If you’ve already some programming experience, please feel free to jump ahead to creating the Flask app.

Remember: If you get stuck at any time, please look out for Ciara, Caroline or Dave.


## Set Up: 

Repl.it is an online read–eval–print loop, which gives a programmer an integrated development environment. It allows you to code, compile and run code in lots of programming languages. It even has courses to help you learn!

You can create a user account for Repl.it using your email or sign in with Github if you have a Github account. Once you are logged in, go to the languages section and select Python from the Popular section and a new Python project will be created for you.



## PYTHON EXERCISES

We’ll start with the the basics of Python and some exercises.

### Python Version
When you are learning Python you may notice people talking about what version of python they are using: Python 2 or Python 3. For this session, we will be using Python 3. Here is a post explaining the history between the versions, the differences between them as well as talking about which version you should learn if you are starting out: https://learntocodewith.me/programming/python/python-2-vs-python-3/ 

You can find out what version of python you are using by importing ‘sys’ and printing ‘sys.version’. Try it out for yourself - it should output something like 3.6.7 which is a version of Python 3.


import sys
print(sys.version)

Keywords in Python
Python has a number keywords. In a programming language, a key word belongs to the language and cannot be used to name any other identifier.

You can find out what the keyword of Python by importing ‘keywords’ and printing the key word list.

import keyword
print(keyword.kwlist)

You can find out more about what each keyword is used for here: https://www.programiz.com/python-programming/keyword-list 



## Input and Output

Try entering the following into your Repl.it environment, in the ‘main.py’ section on left, then the ‘run’ button to see the output on the Python console to the right.

1.print("Hello World!")
2. print("Enter your name:")
name = input()
print("Hello " + name)                                                                                                        

3. age = int(input("Enter your age: "))
print( name + " you are " + str(age) + " years old")


### Quick Maths

Python can carry out calculations and uses the standard order of operations (PEMDAS: Parenthesis, Exponents, Multiplication, Division, Subtraction)
Mathematical Operators
Addition: +
Subtraction: -
Multiplication: *
Division: /
Modulo: %
Can you find the answers to the below problems? You can enter these directly into the Python console (right screen) on Repl.it.
5962 subtract 2958 eg 5962-2958
-175 add 236
36 multiplied by 17
2041 divided by 13
the remainder when 24824 is divided by 17

 
## Variables and Data Types
A variable is a like box with something in it. Boxes can be different sizes and store different things. A data type is used to say what type of data is in the box.

Declaring Variables in Python
Variables let you assign a value to a name, which can be used to refer to the value later in the program.
Python is dynamically typed. This means that you do not have to declare the type of each variable. In statically languages like C# and Java, you have to explicitly declare variables using their data type.
Declare a variable by giving it a name and assign it a value using the equals sign '=':
eg: myName = "Ciara"  

Assigning a variable a value, won't produce any output. 
Use the print( ) function to output the value of a variable:
print(myName)

Variables in Python can be reassigned, to change their value. Variables do not have a specific type, so you can assign a string to a variable, and later re-assign an integer to the same variable. More about basic types in Python
This is not good practice and can lead to mistakes, so try to avoid overwriting the same variable with different types:

myAge = "twenty one"
print(myAge)
myAge = 21
print(myAge)


 
Python provides support for different data types:
Integers
Floats
Strings
Booleans

Examples:

myInt = 17
myDecimal = 85.6
myString = "Hello World"
myBoolean = false
Control Flow
We can use control flow statements to control the flow of a program. The compiler will execute statements depending on the outcome of the control flow statements. 
Selection
If statements

An if statement is a conditional (evaluates to true or false) that when satisfied ( is true ), some piece of code is executed. In ‘main.py’ try entering the below ‘livesLeft’ if statement and then changing ‘livesLeft’ from 3  to 0, 1, 2, or 3 to see a different output:

livesLeft = 3
if(livesLeft == 3):
    print("Full health")
elif(livesLeft == 2):
    print("Two lives left")
elif(livesLeft == 1):
    print("One life left")
else:
    print("Game over")



### More about conditionals: https://realpython.com/python-conditional-statements/ 

Iteration
for statement
while statement
 
A for loop executes a piece of code a number of times. The number of times to execute the code is given in advance. Check out this post for more info on for loops: https://realpython.com/python-for-loop/ 
Try executing the following for statements in ‘main.py ‘to see what happens
for i in range(1,10):
  print(i * 2)
  
for letter in 'This is a string':
  print(letter)
 
shopping_list_tuple = ['bagels', 'bananas', 'flour', 'avocado', 'pasta']
for item in shopping_list_tuple:
  print(item)
 
A while loop is also used to execute a piece of repeatedly. With a while loop, the number of times to execute the piece of code may not be known. A while loop will execute a piece of code as long as a certain condition is met. Check out this post for more info on while loops: https://realpython.com/python-while-loop/ 
Try executing the following while statement in ‘main.py’ to see what happens
  
items_in_basket = 0
while items_in_basket < 5:
  print(items_in_basket)
  items_in_basket = items_in_basket + 1

 

## More Python Exercises:

Have a go at the following Python Exercises 1-5. There are notes and solutions to guide you through:

https://www.practicepython.org/

Repl.it also has a Python course that you can try as well: https://repl.it/community 


### Flask App:

You can try the following tutorial to build a simple Flask app. You will be able to use your Repl.it environment for this.

https://pythonspot.com/flask-web-app-with-python/ 


## Python Reading for Beginners:

https://realpython.com/python-beginner-tips/

https://docs.python-guide.org/intro/learning/

https://guide.freecodecamp.org/python/

https://simpleprogrammer.com/get-started-learning-python/

https://pythonprogramming.net/ 

