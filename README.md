# Learn-_Python_1

## Python
Python is a general-purpose, versatile, and powerful programming language. It’s a great first language because Python code is concise and easy to read. Whatever you want to do, python can do it. From web development to machine learning to data science, Python is the language for you.

## Python Basic
### Introduction (variable and print statement)
#### Variable
A variable is a placeholder for data that Python can remember later in the coding process when an action is needed. Technically speaking, the variable serves as an address for where the data is kept in memory. A Python variable can be allocated a value of one type, then reassigned a value of another type.


notes:
To make a value in a variable, the "=" operator can be used between the variable name and the value to be stored.

Ex:  
 ```python
  x = 10
  y = "John"
   ```
#### Print Function
The print() function sends the provided message to the screen or a standard output device. The message can be a string or any other object; the object will be converted to a string before being printed to the screen.
Ex:  
 ```python
  x = 10
  y = "John"

  print(x)
  print(y)
   ```
Output :
 ```
   10
   John
   ```
### Input() function
This set of code requests user input and stores it in the message variable. Inputs are automatically saved as strings. As a result, always convert to integers before performing any mathematical operations.
 ```python
   print('Enter your name:')
   x = input()
   print('Hello, ' + x)
   ```

## String Operations 
To print a string and a variable in Python, we can use the print() function. there are several methods as follows:
- Concatenate variables in the Print() statement: separating each with comma
- String Format
- Modulo Operator (%) with Argument Specifiers
  We use argument specifiers like %s, %d, etc., in strings which are then replaced by some
  value.
  Commonly used:
![alt text](?raw=true) 

## Data type
A data type is an attribute associated with a piece of data that tells a computer system how to interpret its value. Python Data Types are used to define the type of a variable. It defines what type of data we are going to store in a variable. The data stored in memory can be of many types.

### Number
The numeric data type in Python represents the data that has a numeric value. A numeric value can be an integer, a floating number, or even a complex number.

####  int
The integer data type is a numeric data type that holds whole numbers.

####  float
The float data type is used for variables that have fractional / decimal values.

####  complex
Complex data types. It represents imaginary values.

### String
In Python, a string is a sequence of characters.
Strings in python are surrounded by either single quotation marks, or double quotation marks.

### Boolean
In programming you often need to know if an expression is True or False.
When you compare two values, the expression is evaluated and Python returns the Boolean answer

### List [ ]
The list data type is a collection data type that is ordered and also changeable. We can define this data type with square brackets [ ] in Python.

Ex : 
 ```python
   a = [1, 2, 3]
   ```

### Tuple ( )
Tuple is a type of list whose elements cannot be changed. Generally, tuples are used for data that is write-once, and can be executed more quickly. Tuples are defined by brackets and elements are separated by commas.

Ex :
 ```python
   a = (1, 2, 3])
   ```
### Set { }
Set is a collective data type that is unique, unordered and unchangeable where all values must be unique, and it cannot be accessed via index (because it is not ordered), and it cannot be edited (but can be added and deleted).

Ex :
 ```python
   a = {1, 2, 3}
   ```
### Union
The union method returns a set that contains all items from the original set, and all items from the specified set(s).
### Intersection
The intersection method returns a set that contains the similarity between two or more sets.
### Dictionary
A dictionary in Python is a collection of unordered key-value pairs. Dictionaries can be used to convey small to large data. To access the data we have to know the key. In the Python Dictionary it is defined with curly braces and additional definitions:
- Each pair-key value element is separated by a comma (,)
- Key and value are separated by a colon (:)
- Keys and values can be any type of variable / object

## Python Comparison Operators
![alt text](https://github.com/andhitogalih/Learn-_Python_1/blob/main/public/image/Aritmatic%20Operators.png?raw=true) 

## Python Aritmetic Operators
![alt text](https://github.com/andhitogalih/Learn-_Python_1/blob/main/public/image/Comparision%20Operator.png?raw=true)

## Conditional Expressions
A conditional expression evaluates a series of conditions for each row of a table and returns the matching result expression. Conditional expressions can also be combined and nested like other expressions.

### If
An if statement is a condition statement that checks a condition and executes it if it is true. It is also a control flow statement, which employs decision-making to regulate the flow of execution.

### If-else Statement
The if-else statement is used to execute both the true part and the false part of a given condition. If the condition is true, the if block code is executed and if the condition is false, the else block code is executed.

### Elif(else-if)
‘Elif’ stands for ‘else if’ and is used in Python programming to test multiple conditions. It is written after an if statement in Python to verify an alternative condition if the first one is false. The code block enclosed by the elif expression will be executed only if its condition is true.

## Looping
Looping means repeating something over and over until a particular condition is satisfied. A for loop in Python is a control flow statement that is used to repeatedly execute a group of statements as long as the condition is satisfied.
### For
In Python, the For Loop is used to iterate over a list, tuple, or string, as well as other iterable objects. Iterating over a sequence involves going through each element one by one.

Syntax :
'''
for iterating_var in sequence:
   statements(s)
'''

### While
A while loop in Python is a control flow statement that allows a block of code to be executed repeatedly based on a given Boolean condition. In other words, the while loop will keep iterating and running the code block inside of it until the specified condition evaluates to False.
Syntax :
'''
while condition:
    statements
'''

## Break
A break statement in Python alters the flow of a loop by terminating it once a specified condition is met.

## Countinue
The continue statement in Python is used to skip the remaining code inside a loop for the current iteration only.

## List Comprehension
List Comprehension is a way to generate new lists based on previously existing lists or iterables. List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

Syntax : 
'''
newlist = [expression for item in iterable if condition == True]
'''
