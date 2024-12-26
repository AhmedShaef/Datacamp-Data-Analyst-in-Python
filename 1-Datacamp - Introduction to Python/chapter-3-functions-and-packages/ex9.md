
#  Different ways of importing

```
Exercise ID 14279
```

##  Assignment 

There are several ways to import packages and modules into Python. Depending on the import call, you'll have to use different Python code.

Suppose you want to use the function [`inv()`](http://docs.scipy.org/doc/numpy-1.10.0/reference/generated/numpy.linalg.inv.html), which is in the `linalg` subpackage of the `scipy` package. You want to be able to use this function as follows:

```
my_inv([[1,2], [3,4]])

```

Which `import` statement will you need in order to run the above code without an error?

##  Answers 
1. `import scipy`
1. `import scipy.linalg`
1. `from scipy.linalg import my_inv`
1. `from scipy.linalg import inv as my_inv`


##  Hints 

Try the different import statements in the IPython shell and see which one causes the line `my_inv([[1, 2], [3, 4]])` to run without errors.



##  Solution 

No solution was found.


