# Mean-Variance-Standard Deviation Calculator

This is the boilerplate for the Mean-Variance-Standard Deviation Calculator project.
Here is the README updated with emojis and an example image:

# 📊 Mean, Variance, and Standard Deviation Calculator

This program implements a `calculate()` 🧮function that calculates the mean, variance, standard deviation, max, min and sum of the rows, columns and flattened elements of a 3x3 matrix 👀 passed in as a 9 digit list.  

## Usage

```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
```      
              
The `calculate()` function returns a dictionary with the following keys:
                        
 - `mean`: List containing the mean of rows, columns and flattened matrix   
 - `variance`: List containing the variance of rows, columns and flattened matrix  
 - `standard deviation`: List containing the standard deviation of rows, columns and flattened matrix   
 - `max`: List containing the max of rows, columns and flattened matrix 
 - `min`: List containing the min of rows, columns and flattened matrix      
 - `sum`: List containing the sum of rows, columns and flattened matrix

The function will raise a `ValueError` 🛑 if the input list has less than 9 elements.

![Example Output](output.png)

Hope this helps explain the `calculate()` 💡 function and how to use it!







Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator
