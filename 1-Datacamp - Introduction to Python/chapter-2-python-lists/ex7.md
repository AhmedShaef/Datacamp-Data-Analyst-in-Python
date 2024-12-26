
#  Slicing and dicing

```
Exercise ID 14261
```

##  Assignment 

Selecting single values from a list is just one part of the story. It's also possible to **slice** your list, which means selecting multiple elements from your list. Use the following syntax:

```
my_list[start:end]

```

The `start` index will be included, while the `end` index is **not**.

The code sample below shows an example. A list with `"b"` and `"c"`, corresponding to indexes 1 and 2, are selected from a list `x`:

```
x = ["a", "b", "c", "d"]
x[1:3]

```

The elements with index 1 and 2 are included, while the element with index 3 is not.

##  Instructions 

- Use slicing to create a list, `downstairs`, that contains the first 6 elements of `areas`.
- Do a similar thing to create a new variable, `upstairs`, that contains the last 4 elements of `areas`.
- Print both `downstairs` and `upstairs` using [`print()`](https://docs.python.org/3/library/functions.html#print).



```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Use slicing to create downstairs


# Use slicing to create upstairs


# Print out downstairs and upstairs
```

##  Hints 

- Use the brackets `[0:6]` to build `downstairs`.
- Use the brackets `[6:10]` to build `upstairs`.
- Simply add two [`print()`](https://docs.python.org/3/library/functions.html#print) calls to the script to print out `downstairs` and `upstairs`.



##  Solution 

```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Use slicing to create downstairs
downstairs = areas[0:6]

# Use slicing to create upstairs
upstairs = areas[6:10]

# Print out downstairs and upstairs
print(downstairs)
print(upstairs)
```


