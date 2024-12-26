
#  Subsetting NumPy Arrays

```
Exercise ID 14284
```

##  Assignment 

You've seen it with your own eyes: Python lists and `numpy` arrays sometimes behave differently. Luckily, there are still certainties in this world. For example, subsetting (using the square bracket notation on lists or arrays) works exactly the same. To see this for yourself, try the following lines of code in the IPython Shell:

```
x = ["a", "b", "c"]
x[1]

np_x = np.array(x)
np_x[1]

```

The script in the editor already contains code that imports `numpy` as `np`, and stores both the height and weight of the MLB players as `numpy` arrays. `height_in` and `weight_lb` are available as regular lists.

##  Pre exercise code 

```
import pandas as pd
mlb = pd.read_csv("http://assets.datacamp.com/course/intro_to_python/baseball.csv")
height_in = mlb['Height'].tolist()
weight_lb = mlb['Weight'].tolist()
```



##  Instructions 

- Subset `np_weight_lb` by printing out the element at index 50.
- Print out a sub-array of `np_height_in` that contains the elements at index 100 up to **and including** index 110.



```
# Import numpy
import numpy as np

# Store weight and height lists as numpy arrays
np_weight_lb = np.array(weight_lb)
np_height_in = np.array(height_in)

# Print out the weight at index 50


# Print out sub-array of np_height_in: index 100 up to and including index 110

```

##  Hints 

- Make sure to wrap a [`print()`](https://docs.python.org/3/library/functions.html#print) call around your subsetting operations.
- Use `[100:111]` to get the elements from index 100 up to and including index 110.



##  Solution 

```
# Import numpy
import numpy as np

# Store weight and height lists as numpy arrays
np_weight_lb = np.array(weight_lb)
np_height_in = np.array(height_in)

# Print out the weight at index 50
print(np_weight_lb[50])

# Print out sub-array of np_height_in: index 100 up to and including index 110
print(np_height_in[100:111])
```


