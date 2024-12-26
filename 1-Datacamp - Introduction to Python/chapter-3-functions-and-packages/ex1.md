
#  Familiar functions

```
Exercise ID 14270
```

##  Assignment 

Out of the box, Python offers a bunch of built-in functions to make your life as a data scientist easier. You already know two such functions: [`print()`](https://docs.python.org/3/library/functions.html#print) and [`type()`](https://docs.python.org/3/library/functions.html#type). You've also used the functions [`str()`](https://docs.python.org/3/library/functions.html#func-str), [`int()`](https://docs.python.org/3/library/functions.html#int), [`bool()`](https://docs.python.org/3/library/functions.html#bool) and [`float()`](https://docs.python.org/3/library/functions.html#float) to switch between data types. These are built-in functions as well.

Calling a function is easy. To get the type of `3.0` and store the output as a new variable, `result`, you can use the following:

```
result = type(3.0)

```

The general recipe for calling functions and saving the result to a variable is thus:

```
output = function_name(input)

```

##  Instructions 

- Use [`print()`](https://docs.python.org/3/library/functions.html#print) in combination with [`type()`](https://docs.python.org/3/library/functions.html#type) to print out the type of `var1`.
- Use [`len()`](https://docs.python.org/3/library/functions.html#len) to get the length of the list `var1`. Wrap it in a [`print()`](https://docs.python.org/3/library/functions.html#print) call to directly print it out.
- Use [`int()`](https://docs.python.org/3/library/functions.html#int) to convert `var2` to an integer. Store the output as `out2`.



```
# Create variables var1 and var2
var1 = [1, 2, 3, 4]
var2 = True

# Print out type of var1


# Print out length of var1


# Convert var2 to an integer: out2

```

##  Hints 

- Call the [`type()`](https://docs.python.org/3/library/functions.html#type) function like this: `type(var1)`.
- Call [`print()`](https://docs.python.org/3/library/functions.html#print) like you did so many times before. Simply put the variable you want to print in parentheses.
- `int(x)` will convert `x` to an integer.



##  Solution 

```
# Create variables var1 and var2
var1 = [1, 2, 3, 4]
var2 = True

# Print out type of var1
print(type(var1))

# Print out length of var1
print(len(var1))

# Convert var2 to an integer: out2
out2 = int(var2)
```


