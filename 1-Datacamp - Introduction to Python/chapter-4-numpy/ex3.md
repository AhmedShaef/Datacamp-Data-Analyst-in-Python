
#  Baseball player's BMI

```
Exercise ID 14360
```

##  Assignment 

The MLB also offers to let you analyze their weight data. Again, both are available as regular Python lists: `height_in` and `weight_lb`. `height_in` is in inches and `weight_lb` is in pounds.

It's now possible to calculate the BMI of each baseball player. Python code to convert `height_in` to a `numpy` array with the correct units is already available in the workspace. Follow the instructions step by step and finish the game! `height_in` and `weight_lb` are available as regular lists.

##  Pre exercise code 

```
import pandas as pd
mlb = pd.read_csv("http://assets.datacamp.com/course/intro_to_python/baseball.csv")
height_in = mlb['Height'].tolist()
weight_lb = mlb['Weight'].tolist()
import numpy as np
```



##  Instructions 

- Create a `numpy` array from the `weight_lb` list with the correct units. Multiply by `0.453592` to go from pounds to kilograms. Store the resulting `numpy` array as `np_weight_kg`.
- Use `np_height_m` and `np_weight_kg` to calculate the BMI of each player. Use the following equation: $$ \mathrm{BMI} = \frac{\mathrm{weight (kg)}}{\mathrm{height (m)}^2}$$ Save the resulting `numpy` array as `bmi`.
- Print out `bmi`.



```
# Import numpy
import numpy as np

# Create array from height_in with metric units: np_height_m
np_height_m = np.array(height_in) * 0.0254

# Create array from weight_lb with metric units: np_weight_kg


# Calculate the BMI: bmi


# Print out bmi

```

##  Hints 

- Use a similar approach as the code that calculates `np_height_m`. This time, though, the you have to work with `weight` and multiply with `0.453592`.
- To calculate the `bmi`, you will need the `/` and `**` operators. Recall `**` is for exponents.
- To print out a variable `x`, type `print(x)` in the script.



##  Solution 

```
# Import numpy
import numpy as np

# Create array from height_in with metric units: np_height_m
np_height_m = np.array(height_in) * 0.0254

# Create array from weight_lb with metric units: np_weight_kg
np_weight_kg = np.array(weight_lb) * 0.453592

# Calculate the BMI: bmi
bmi = np_weight_kg / np_height_m ** 2

# Print out bmi
print(bmi)
```


