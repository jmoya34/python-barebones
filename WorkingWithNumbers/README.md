# Math operations in python
## There are several math operations we can use in python such as multiplication, division, adition, and subtraction.
### examples of math operations:
```python
# multiplication uses *
num9 = 3 * 3

# division uses
num3 = 9 / 3

# addition uses +
num2 = 1 + 1

#subtraction uses -
num1 = 2-1

print(num1)
print(num2)
print(num3)
print(num9)
```

# Introducing the modulus ```%```
## People hesistate to learn the modules, but I encourage you to learn
The modulus ```%``` in the most simple explanation is the remainder of when you divide a number. When any number is divided by it's self it equals 1, and when using % in python will return 0.

Examples in python:
```python
print(2 % 2) # since 2/2 = 1 in math. Python will return 0
print(3 % 2) # since 3/2 will leave a remainder of 1 python will return 1
print(4 % 2) # 4/2 leaves no remainder therefore python returns a 0
print(0 % 2) # 0/2 = 0 so python returns 0


print(1 % 2) 
# 1/2 in this case there is no remainder however since it is under 2 it will 
# return the same value that is being divided.
```

# Using multiple math operations on one line
Python uses a order of operations when there are multiple math commands going on in one line. If we had an equation such as 10 - 4 / 2 * 3 + 2. Python would follow a specific order in which it would excute that command. Python does its order of operations as from top to bottom:
* Parenthesis
* Exponent
* Multiplication/Division/Modululs
* Addition/Subtraction

Try to predect what the number will be for the following code
```python
number = 10 - 4 / 2 * 3 + (2-1)
print(number)

# creating exponents is written as
print(3 ** 3) # returns a value of 27 because 3*3*3=27
```
