Preprocessing Tasks
1. Loading the dataset into a Panda’s DataFrame (free points)
2. Correcting the incorrect values
a. Replacing outliers with np.nan
b. Replace incorrect data types in columns with np.nan
i. Remove integers from a column that is supposed to be strings
ii. Remove strings from a column that is supposed to be ints/floats
c. Replacing missing numeric values with the column's mean value
i. Np.nan -> some mean value
d. Replacing missing categorical values with the column’s most common value
i. np.nan -> most common column value
3. One Hot Encode the following columns:
a. Marital Status
b. Employment Status
c. Drop the categorical columns after you have OHE and appended the values
4. Binary Encode the following column:
a. Car Ownership
5. Custom Encode the following column to fit the following set:
a. Internet Usage {Low, Medium, High} -> {0, .5, 1}
6. Discretize the “final math grade” into binary bins
a. You need to add 5 new columns to your dataframe
i. math_grade_A, math_grade_B, math_grade_C, math_grade_D, math_grade_F
b. If a sample has a math grade of 91:
i. [1, 0, 0, 0, 0]
c. DROP the final math grade column after you are done
7. Min-Max Scale your dataset
