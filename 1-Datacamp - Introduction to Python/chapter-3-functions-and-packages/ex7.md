
#  Import package

```
Exercise ID 14277
```

##  Assignment 

As a data scientist, some notions of geometry never hurt. Let's refresh some of the basics.

For a fancy clustering algorithm, you want to find the circumference, \(C\), and area, \(A\), of a circle. When the radius of the circle is `r`, you can calculate \(C\) and \(A\) as:

$$C = 2 \pi r$$
$$A = \pi r^2 $$

In Python, the symbol for exponentiation is `**`. This operator raises the number to its left to the power of the number to its right. For example `3**4` is `3` to the power of `4` and will give `81`.

To use the constant `pi`, you'll need the `math` package. A variable `r` is already coded in the script. Fill in the code to calculate `C` and `A` and see how the [`print()`](https://docs.python.org/3/library/functions.html#print) functions create some nice printouts.

##  Instructions 

- Import the `math` package. Now you can access the constant `pi` with `math.pi`.
- Calculate the circumference of the circle and store it in `C`.
- Calculate the area of the circle and store it in `A`.



```
# Import the math package


# Definition of radius
r = 0.43

# Calculate C
C = 0

# Calculate A
A = 0

# Build printout
print("Circumference: " + str(C))
print("Area: " + str(A))
```

##  Hints 

- You can simply use `import math`, and then refer to `pi` with `math.pi`.
- Use the equation in the assignment text to find `C`. Use `*`
- Use the equation in the assignment text to find `A`. Use `*` and `**`.



##  Solution 

```
# Import the math package
import math

# Definition of radius
r = 0.43

# Calculate C
C = 2 * r * math.pi

# Calculate A
A = math.pi * r ** 2

# Build printout
print("Circumference: " + str(C))
print("Area: " + str(A))
```


