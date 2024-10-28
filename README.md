# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 8 Assignment

#### Assigned: October 28, 2024

#### Due: November 4, 2024 (before 3:30 pm)

---

#### Learning Goals

1.  Utilize graphical analysis to determine starting points for bracketed and non-bracketed root finding methods, and
1.  Implement a bracketed and non-bracketed root finding method.

#### Description

Conside the function shown below on the interval of [0.5,1.0].

$$
4x^3-3x=0
$$


#### Step 1

Edit the first cell (markdown), to update your personal information for laboratory 8.

#### Step 2

In cell two, complete the following steps:
+  Create a user-defined function for equation provided in the description,
+  Vectorize the user-defined function,
+  Create an array for the *x-*values on the interval of [0.5, 1.0] that contains at least 100 points,
+  Create an array for the *y-*values using the vectorized function that contains the values of the vectorized *x-*values, 
+  Use Matplotlib to create an x-y graph, and
+  Identify a pair of starting values that brackets the root.

#### Step 3

In cell three, implement one of the bracketed root finding methods using the start values found in step two to find the root with a tolerance of 10^-5. Your code in cell three should print the value of the root and the error.

#### Step 4

In cell four, implement one of the non-bracketed root find methods for the function described in the description. Use one of the bracketing values identified in step as the starting value. Find the root with a tolerance of 10^-5. Your code in cell three should print the value of the root and the error.

#### Step 5

After running and testing your program, save the Jupyter Notebook. Upload your repository using GitHub desktop.