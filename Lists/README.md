# Using Lists in Python

## Lists are a data type designed to store multiple pieces of information
When you find yourself creating multiple variables in your code, you will find using list extremely usefull.

### Creating a list:
```python
my_list = []
```
Creating a list is similar to creating a variable except now we are assigning hardbrackets to a variable. The list created in the example does not store information therefore we have to assign it information. 

```python
animals_i_like = ["Dogs", "Cats", "Birds"]
print(animals_i_like)
```
The example above will print out a results
>  ```['Dogs', 'Cats', 'Birds']```

# Reteriving information from list
### Lists are sorted in an index which mean the location of where something in the list matters. Our lists index starts at the number 0.

If we look at the previous example with the list we created and wanted to retrieve what my first favorite animal was then we would have to use the command

```python
animals_i_like = ["Dogs", "Cats", "Birds"]
print(animals_i_like[0])
```
and the expected output would be
> ```Dogs```

## Picking a number bigger than the number of items in a list results in an error. 
A command error done with list is trying to retrieve an item from an index number that does not exist. In the example we did with my favorite animals the range is 0-2 where 0 is assigned to "Dogs", 1 "Cats", and 2 "Birds". Therefore if we try to run the command:

```python
animals_i_like = ["Dogs", "Cats", "Birds"]
print(animals_i_like[3]) # expect an error
```

# Changing values inside of a list
