
#  Your First 2D NumPy Array

```
Exercise ID 14774
```

##  Assignment 

Before working on the actual MLB data, let's try to create a 2D `numpy` array from a small list of lists.

In this exercise, `baseball` is a list of lists. The main list contains 4 elements. Each of these elements is a list containing the height and the weight of 4 baseball players, in this order. `baseball` is already coded for you in the script.

##  Instructions 

- Use [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) to create a 2D `numpy` array from `baseball`. Name it `np_baseball`.
- Print out the type of `np_baseball`.
- Print out the `shape` attribute of `np_baseball`. Use `np_baseball.shape`.



```
# Import numpy
import numpy as np

# Create baseball, a list of lists
baseball = [[180, 78.4],
            [215, 102.7],
            [210, 98.5],
            [188, 75.2]]

# Create a 2D numpy array from baseball: np_baseball


# Print out the type of np_baseball


# Print out the shape of np_baseball

```

##  Hints 

- `baseball` is already coded for you in the script. Call [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) on it and store the resulting 2D `numpy` array in `np_baseball`.
- Use [`print()`](https://docs.python.org/3/library/functions.html#print) in combination with [`type()`](https://docs.python.org/3/library/functions.html#type) for the second instruction.
- `np_baseball.shape` will give you the dimensions of the `np_baseball`. Make sure to wrap a [`print()`](https://docs.python.org/3/library/functions.html#print) call around it.



##  Solution 

```
# Import numpy
import numpy as np

# Create baseball, a list of lists
baseball = [[180, 78.4],
            [215, 102.7],
            [210, 98.5],
            [188, 75.2]]

# Create a 2D numpy array from baseball: np_baseball
np_baseball = np.array(baseball)

# Print out the type of np_baseball
print(type(np_baseball))

# Print out the shape of np_baseball
print(np_baseball.shape)
```


