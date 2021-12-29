Order of executing scripts:

1. custom_categorial - Creates a new categorical variable based on the 'horsepower' variable
     Exports into:
        car_data_custom.xlsx

2.  selection - Selects only the cars that run on gas and have the engine situated in the front of the car. This selection is based on the low amount of rows of the other category for both variables.
     Exports into:
        car_data_selection.xlsx

3.  desc_:num/categ - Descriptive statistics for numerical and categorical variables.
     

4.  outliers_clean - Finds the outliers (based on distribution) for specified variable, with posibility to remove them.
        Exports into:
                car_data_selection.xlsx (overwrite if clean up was done)
                car_data_clean.xlsx     (this is the dataset ready for regression)

5.  mean_tests - Tests multiple means for the clean dataset 

6.  reg_simple - NOT YET IMPLEMENTED

7.  reg_multiple - Multiple regression with 'price' as dependant variable

8. reg_nonlinear  NOT YET IMPLEMENTED