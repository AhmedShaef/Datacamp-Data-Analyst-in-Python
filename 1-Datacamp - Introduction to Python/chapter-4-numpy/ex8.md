
#  Baseball data in 2D form

```
Exercise ID 14775
```

##  Assignment 

You have another look at the MLB data and realize that it makes more sense to restructure all this information in a 2D `numpy` array. This array should have 1015 rows, corresponding to the 1015 baseball players you have information on, and 2 columns (for height and weight).

The MLB was, again, very helpful and passed you the data in a different structure, a Python list of lists. In this list of lists, each sublist represents the height and weight of a single baseball player. The name of this embedded list is `baseball`.

Can you store the data as a 2D array to unlock `numpy`'s extra functionality? `baseball` is available as a regular list of lists.

##  Pre exercise code 

```
import pandas as pd
baseball = pd.read_csv("http://assets.datacamp.com/course/intro_to_python/baseball.csv")[['Height', 'Weight']].to_numpy().tolist()
import numpy as np
```



##  Instructions 

- Use [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) to create a 2D `numpy` array from `baseball`. Name it `np_baseball`.
- Print out the `shape` attribute of `np_baseball`.



```
# Import numpy package
import numpy as np

# Create a 2D numpy array from baseball: np_baseball


# Print out the shape of np_baseball

```

##  Hints 

- `baseball` is already available in the Python environment. Call [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) on it and store the resulting 2D `numpy` array in `np_baseball`.
- `np_baseball.shape` will give the dimensions of the `np_baseball`. Make sure to wrap a [`print()`](https://docs.python.org/3/library/functions.html#print) call around it.



##  Solution 

```
# Import numpy package
import numpy as np

# Create a 2D numpy array from baseball: np_baseball
np_baseball = np.array(baseball)

# Print out the shape of np_baseball
print(np_baseball.shape)
```


