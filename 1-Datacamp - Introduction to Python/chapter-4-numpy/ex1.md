
#  Your First NumPy Array

```
Exercise ID 14294
```

##  Assignment 

In this chapter, we're going to dive into the world of baseball. Along the way, you'll get comfortable with the basics of `numpy`, a powerful package to do data science.

A list `baseball` has already been defined in the Python script, representing the height of some baseball players in centimeters. Can you add some code here and there to create a `numpy` array from it?

##  Pre exercise code 

```
import numpy as np
```



##  Instructions 

- Import the `numpy` package as `np`, so that you can refer to `numpy` with `np`.
- Use [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) to create a `numpy` array from `baseball`. Name this array `np_baseball`.
- Print out the type of `np_baseball` to check that you got it right.



```
# Import the numpy package as np


# Create list baseball
baseball = [180, 215, 210, 210, 188, 176, 209, 200]

# Create a numpy array from baseball: np_baseball


# Print out type of np_baseball

```

##  Hints 

- `import numpy as np` will do the trick. Now, you have to use `np.fun_name()` whenever you want to use a `numpy` function.
- [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) should take on input `baseball`. Assign the result of the function call to `np_baseball`.
- To print out the type of a variable `x`, simply type `print(type(x))`.



##  Solution 

```
# Import the numpy package as np
import numpy as np

# Create list baseball
baseball = [180, 215, 210, 210, 188, 176, 209, 200]

# Create a NumPy array from baseball: np_baseball
np_baseball = np.array(baseball)

# Print out type of np_baseball
print(type(np_baseball))
```


