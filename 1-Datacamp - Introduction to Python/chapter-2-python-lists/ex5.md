
#  Subset and conquer

```
Exercise ID 14259
```

##  Assignment 

Subsetting Python lists is a piece of cake. Take the code sample below, which creates a list `x` and then selects "b" from it. Remember that this is the second element, so it has index 1. You can also use negative indexing.

```
x = ["a", "b", "c", "d"]
x[1]
x[-3] # same result!

```

Remember the `areas` list from before, containing both strings and floats? Its definition is already in the script. Can you add the correct code to do some Python subsetting?

##  Instructions 

- Print out the second element from the `areas` list (it has the value `11.25`).
- Subset and print out the last element of `areas`, being `9.50`. Using a negative index makes sense here!
- Select the number representing the area of the living room (`20.0`) and print it out.



```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Print out second element from areas
print(areas[_])

# Print out last element from areas
print(areas[__])

# Print out the area of the living room
print(areas[_])
```

##  Hints 

- Use `x[1]` to select the second element of a list `x`. Make sure to wrap your subsetting operation in a [`print()`](https://docs.python.org/3/library/functions.html#print) call.
- Use `x[-1]` to select the last element of a list `x`. Make sure to wrap your subsetting operation in a [`print()`](https://docs.python.org/3/library/functions.html#print) call.
- The number representing the area of the living room is the 6th element in the list, so you'll need `[5]` here.



##  Solution 

```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Print out second element from areas
print(areas[1])

# Print out last element from areas
print(areas[-1])

# Print out the area of the living room
print(areas[5])
```


