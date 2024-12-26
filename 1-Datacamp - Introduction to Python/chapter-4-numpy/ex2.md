
#  Baseball players' height

```
Exercise ID 14349
```

##  Assignment 

You are a huge baseball fan. You decide to call the MLB (Major League Baseball) and ask around for some more statistics on the height of the main players. They pass along data on more than a thousand players, which is stored as a regular Python list: `height_in`. The height is expressed in inches. Can you make a `numpy` array out of it and convert the units to meters?

`height_in` is already available and the `numpy` package is loaded, so you can start straight away (Source: [stat.ucla.edu](https://wiki.stat.ucla.edu/socr/index.php/SOCR_Data_MLB_HeightsWeights)).

##  Pre exercise code 

```
import pandas as pd
mlb = pd.read_csv("http://assets.datacamp.com/course/intro_to_python/baseball.csv")
height_in = mlb['Height'].tolist()
import numpy as np
```



##  Instructions 

- Create a `numpy` array from `height_in`. Name this new array `np_height_in`.
- Print `np_height_in`.
- Multiply `np_height_in` with `0.0254` to convert all height measurements from inches to meters. Store the new values in a new array, `np_height_m`.
- Print out `np_height_m` and check if the output makes sense.



```
# Import numpy
import numpy as np

# Create a numpy array from height_in: np_height_in


# Print out np_height_in


# Convert np_height_in to m: np_height_m


# Print np_height_m

```

##  Hints 

- Use [`np.array()`](http://docs.scipy.org/doc/numpy-1.10.0/glossary.html#term-array) and pass it `height`. Store the result in `np_height_in`.
- To print out a variable `x`, type `print(x)` in the Python script.
- Perform calculations as if `np_height_in` is a single number: `np_height_in * conversion_factor` is part of the answer.
- To print out a variable `x`, type `print(x)` in the Python script.



##  Solution 

```
# Import numpy
import numpy as np

# Create a numpy array from height_in: np_height_in
np_height_in = np.array(height_in)

# Print out np_height_in
print(np_height_in)

# Convert np_height_in to m: np_height_m
np_height_m = np_height_in * 0.0254

# Print np_height_m
print(np_height_m)
```


