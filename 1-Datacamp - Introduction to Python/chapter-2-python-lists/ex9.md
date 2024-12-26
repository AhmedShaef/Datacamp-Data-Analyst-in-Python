
#  Subsetting lists of lists

```
Exercise ID 14263
```

##  Assignment 

You saw before that a Python list can contain practically anything; even other lists! To subset lists of lists, you can use the same technique as before: square brackets. Try out the commands in the following code sample in the IPython Shell:

```
x = [["a", "b", "c"],
     ["d", "e", "f"],
     ["g", "h", "i"]]
x[2][0]
x[2][:2]

```

`x[2]` results in a list, that you can subset again by adding additional square brackets.

What will `house[-1][1]` return? `house`, the list of lists that you created before, is already defined for you in the workspace. You can experiment with it in the IPython Shell.

##  Pre exercise code 

```
house = [["hallway", 11.25],
         ["kitchen", 18.0],
         ["living room", 20.0],
         ["bedroom", 10.75],
         ["bathroom", 9.50]]
```



##  Answers 
1. A float: the kitchen area
1. A string: `"kitchen"`
1. A float: the bathroom area
1. A string: `"bathroom"`


##  Hints 

`house[-1]` selects the last element of `house`, which is the list `["bathroom", 9.50]`. What's the result if you then subset this sublist with `[1]`? You can always try out the command in the IPython Shell!



##  Solution 

No solution was found.


