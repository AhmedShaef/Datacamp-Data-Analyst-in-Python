
#  List Methods

```
Exercise ID 14274
```

##  Assignment 

Strings are not the only Python types that have methods associated with them. Lists, floats, integers and booleans are also types that come packaged with a bunch of useful methods. In this exercise, you'll be experimenting with:

- [`index()`](https://docs.python.org/3/library/stdtypes.html#str.index), to get the index of the first element of a list that matches its input and
- [`count()`](https://docs.python.org/3/library/stdtypes.html#str.count), to get the number of times an element appears in a list.

You'll be working on the list with the area of different parts of a house: `areas`.

##  Instructions 

- Use the [`index()`](https://docs.python.org/3/library/stdtypes.html#str.index) method to get the index of the element in `areas` that is equal to `20.0`. Print out this index.
- Call [`count()`](https://docs.python.org/3/library/stdtypes.html#str.count) on `areas` to find out how many times `9.50` appears in the list. Again, simply print out this number.



```
# Create list areas
areas = [11.25, 18.0, 20.0, 10.75, 9.50]

# Print out the index of the element 20.0


# Print out how often 9.50 appears in areas


```

##  Hints 

- To print out the index, wrap the `areas.index(___)` call in a [`print()`](https://docs.python.org/3/library/functions.html#print) function.
- To print out the number of times an element `x` occurs in the list, wrap the `areas.count(___)` call in a [`print()`](https://docs.python.org/3/library/functions.html#print) function.



##  Solution 

```
# Create list areas
areas = [11.25, 18.0, 20.0, 10.75, 9.50]

# Print out the index of the element 20.0
print(areas.index(20.0))

# Print out how often 9.50 appears in areas
print(areas.count(9.50))
```


