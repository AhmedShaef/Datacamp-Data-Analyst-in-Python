
#  Changes in sales over time

```
Exercise ID 1095671
```

##  Assignment 

Line plots are designed to visualize the relationship between two numeric variables, where each data values is connected to the next one. They are especially useful for visualizing the change in a number over time since each time point is naturally connected to the next time point. In this exercise, you'll visualize the change in avocado sales over three years.

`pandas` has been imported as `pd`, and `avocados` is available.

##  Pre exercise code 

```
import pandas as pd
avocados = pd.read_pickle("/usr/local/share/datasets/avoplotto.pkl")
```



##  Instructions 

- Get the total number of avocados sold on each date. **The DataFrame has two rows for each date&mdash;one for organic, and one for conventional**. Save this as `nb_sold_by_date`.
- Create a line plot of the number of avocados sold.
- Show the plot.



```
# Import matplotlib.pyplot with alias plt
import matplotlib.pyplot as plt

# Get the total number of avocados sold on each date
nb_sold_by_date = ____

# Create a line plot of the number of avocados sold by date
____

# Show the plot
____
```

##  Hints 

- Group by date, select the `nb_sold` column, then calculate the sum.
- Call `.plot()`, setting `kind` to `"line"` to create a line plot.
- Your plot won't appear until you display it using a function from `plt`.



##  Solution 

```
# Import matplotlib.pyplot with alias plt
import matplotlib.pyplot as plt

# Get the total number of avocados sold on each date
nb_sold_by_date = avocados.groupby("date")["nb_sold"].sum()

# Create a line plot of the number of avocados sold by date
nb_sold_by_date.plot(kind="line")

# Show the plot
plt.show()
```


