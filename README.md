This project is a Python program that calculates statistical measures such as mean, variance, standard deviation, maximum, minimum, and sum for a 3×3 matrix. The program uses the NumPy library to perform these calculations efficiently.
The function takes a list containing nine numbers as input, converts the list into a 3×3 NumPy array, and computes the required statistical values for rows, columns, and the entire matrix.
Features
Converts a list of 9 numbers into a 3×3 matrix.
Calculates:
Mean
Variance
Standard Deviation
Maximum
Minimum
Sum
Performs calculations for:
Rows
Columns
Flattened matrix
Raises an error if the input list does not contain exactly nine numbers.
Technologies Used
Python
NumPy
Function Description
The main function in this project is calculate().
Input:
A list containing exactly 9 numerical values.
Output:
A dictionary containing statistical calculations for rows, columns, and the flattened matrix.
Example Input
[0,1,2,3,4,5,6,7,8]
Example Output
A dictionary containing mean, variance, standard deviation, max, min, and sum values.
