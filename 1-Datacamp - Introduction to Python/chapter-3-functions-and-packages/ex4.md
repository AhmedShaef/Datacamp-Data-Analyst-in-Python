
#  String Methods

```
Exercise ID 14275
```

##  Assignment 

Strings come with a bunch of methods. Follow the instructions closely to discover some of them. If you want to discover them in more detail, you can always type `help(str)` in the IPython Shell.

A string `place` has already been created for you to experiment with.

##  Instructions 

- Use the [`upper()`](https://docs.python.org/3/library/stdtypes.html#str.upper) method on `place` and store the result in `place_up`. Use the syntax for calling methods that you learned in the previous video.
- Print out `place` and `place_up`. Did both change?
- Print out the number of o's on the variable `place` by calling [`count()`](https://docs.python.org/3/library/stdtypes.html#str.count) on `place` and passing the letter `'o'` as an input to the method. We're talking about the variable `place`, not the word `"place"`!



```
# string to experiment with: place
place = "poolhouse"

# Use upper() on place: place_up


# Print out place and place_up


# Print out the number of o's in place

```

##  Hints 

- You can call the [`upper()`](https://docs.python.org/3/library/stdtypes.html#str.upper) method on `place` without any additional inputs.
- To print out a variable `x`, you can write `print(x)`.
- Make sure to wrap your `place.count(____)` call in a [`print()`](https://docs.python.org/3/library/functions.html#print) function so that you print it out.



##  Solution 

```
# string to experiment with: place
place = "poolhouse"

# Use upper() on place: place_up
place_up = place.upper()

# Print out place and place_up
print(place)
print(place_up)

# Print out the number of o's in place
print(place.count('o'))
```


