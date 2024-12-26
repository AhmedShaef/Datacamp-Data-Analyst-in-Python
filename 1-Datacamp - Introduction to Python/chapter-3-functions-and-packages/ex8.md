
#  Selective import

```
Exercise ID 14278
```

##  Assignment 

General imports, like `import math`, make **all** functionality from the `math` package available to you. However, if you decide to only use a specific part of a package, you can always make your import more selective:

```
from math import pi

```

Let's say the Moon's orbit around planet Earth is a perfect circle, with a radius `r` (in km) that is defined in the script.

##  Instructions 

- Perform a selective import from the `math` package where you only import the `radians` function.
- Calculate the distance travelled by the Moon over 12 degrees of its orbit. Assign the result to `dist`. You can calculate this as `r * phi`, where `r` is the radius and `phi` is the angle in radians. To convert an angle in degrees to an angle in radians, use the [`radians()`](https://docs.python.org/3/library/math.html#math.radians) function, which you just imported.
- Print out `dist`.



```
# Import radians function of math package


# Definition of radius
r = 192500

# Travel distance of Moon over 12 degrees. Store in dist.


# Print out dist

```

##  Hints 

- Use `from math import radians` to do the selective import.
- You can simply use the [`radians()`](https://docs.python.org/3/library/math.html#math.radians) function now. Pass the function the number 12 to get the angle in radians.
- To print out a variable `x`, simply type `print(x)`.



##  Solution 

```
# Import radians function of math package
from math import radians

# Definition of radius
r = 192500

# Travel distance of Moon over 12 degrees. Store in dist.
dist = r * radians(12)

# Print out dist
print(dist)
```


