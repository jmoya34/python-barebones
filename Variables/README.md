# What is a variable?
### Variables are place holders, or we can view them as boxes.

Variables are an extremely import concept in any programming lanugage since they hold anything. They can have numbers, words, letters, or even multiple things at once.

# Creating variables in python
To create a variable in python you give it a name and it can start with any letter, and note you **__NOT__** put a number at the start of a variable.

<br />Good examples include:
```python
name = "Jason Moya"
first_name = "Jason"
last_name = "Moya"
_number_five = 5
```
There will be some special cases where words are made specifically for python such as the words **True**, **False**, **and**, **or**, etc. However you do not need to wory about knowing them all because using an IDE will highlight the words recognized by python. 

<br /> Bad examples of variables are
```python
1coolname = "This will throw an error"
`word = "error"
and = 'This as well'
```

# Why use variables
### There are times we need to reuse words or numbers we are working with

An example would be constantly using the name of someone to print out their name in a game. If we had someone type in their name in a game we can not type in their name for every single time we reference the player. Instead the variable associated with the name can be used.
```python
name = "Joe Mama"

print("Hello", name)
print("Listen", name, "This is very important")
print("The fate of the universe depends on you,", name)
```
Try replacing the name variable to something else and you will see why it's so useful to use variables

# Use ```type()``` method to find what type of variable
You can quickly find out what type of variable a variable is assigned to by using the following code
```python
name = 'This is a string'
number = 1 # when it's a whole number it is called an integer
pi = 3.14 # when there are numbers after the decimal point it is a float

print(type(name))
print(type(number))
print(type(pi))
```
Run the command and you will see in the terminal
```
<class 'str'>
<class 'int'>
<class 'float'>
```
