# MechaCar_Statistical_Analysis

# Project Overview
# The purpose of this project is to help provide MechaCar Car Company statistical testing that provides data based insight on the company, their performance and possible testing they can use to compare their company against their competition.

# D1: Linear Regression to Predict MPG
# This deliverable is asking if there is a relationship between variables and mpg of MechaCar prototypes.
# Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
# To determine which variables provide a non-random amount of variance to the MPG value we have to look at individual p-values. According to our results (Figure 1)ground clearance (p-value = 5.21 x 10 -8 ), vehicle length (p-value = 2.60 x 10 - 12), as well as intercept (p-value = 5.08 x 10 - 8) provided a non-random amount of variance to the mpg values in the dataset. 

# Is the slope of the linear model considered to be zero? Why or why not?
# Based on our results, the p-value is 5.35 x 10-11, which is much smaller than the significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis. That indicates the slope of our linear model is not zero, meaning that there is a significant linear relationship between variables and mpg of MechaCar prototype.

# Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
# According to our results, the  r-squared is 0.7149 and indicates a strong positive linear relationship, therefore it can be confirmed that this linear model effectively predicts mpg of MechaCar prototypes.

# D2: Summary Statistics on Suspension Coils

# The current manufacturing data meets this design specification for all manufacturing lots in total. According to the results (Figure 4) shows that variance is 76.23 PSI, that is within requirements of not exceeding variance 100 PSI.

# D3: T-Tests on Suspension Coils


