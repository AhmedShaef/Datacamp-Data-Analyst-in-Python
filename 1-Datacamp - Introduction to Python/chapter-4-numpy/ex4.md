
#  Lightweight baseball players

```
Exercise ID 14346
```

##  Assignment 

To subset both regular Python lists and `numpy` arrays, you can use square brackets:

```
x = [4 , 9 , 6, 3, 1]
x[1]
import numpy as np
y = np.array(x)
y[1]

```

For `numpy` specifically, you can also use boolean `numpy` arrays:

```
high = y &gt; 5
y[high]

```

The code that calculates the BMI of all baseball players is already included. Follow the instructions and reveal interesting things from the data! `height_in` and `weight_lb` are available as regular lists.

##  Pre exercise code 

```
import pandas as pd
mlb = pd.read_csv("http://assets.datacamp.com/course/intro_to_python/baseball.csv")
height_in = mlb['Height'].tolist()
weight_lb = mlb['Weight'].tolist()
import numpy as np
```



##  Instructions 

- Create a boolean `numpy` array: the element of the array should be `True` if the corresponding baseball player's BMI is below 21. You can use the `&lt;` operator for this. Name the array `light`.
- Print the array `light`.
- Print out a `numpy` array with the BMIs of all baseball players whose BMI is below 21. Use `light` inside square brackets to do a selection on the `bmi` array.



```
# Import numpy
import numpy as np

# Calculate the BMI: bmi
np_height_m = np.array(height_in) * 0.0254
np_weight_kg = np.array(weight_lb) * 0.453592
bmi = np_weight_kg / np_height_m ** 2

# Create the light array


# Print out light


# Print out BMIs of all baseball players whose BMI is below 21

```

##  Hints 

- `bmi &gt; 30` will give you a boolean `numpy` array in which the elements are `True` if the corresponding player's BMI is over 30.
- To print out a variable `x`, type `print(x)` in the Python script.
- `bmi[light]` will return the array you need. Don't forget to wrap a [`print()`](https://docs.python.org/3/library/functions.html#print) call around it!



##  Solution 

```
# Import numpy
import numpy as np

# Calculate the BMI: bmi
np_height_m = np.array(height_in) * 0.0254
np_weight_kg = np.array(weight_lb) * 0.453592
bmi = np_weight_kg / np_height_m ** 2

# Create the light array
light = bmi < 21

# Print out light
print(light)

# Print out BMIs of all baseball players whose BMI is below 21
print(bmi[light])
```


