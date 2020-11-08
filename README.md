# MechaCar_Statistical_Analysis
# (images in image folder)

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
# To reject or fail to reject the null hypothesis the p-value will determine if there is a statistical difference between the observed sample mean and its presumed population mean. According to the result (Figure 3) p-value for all manufacturing lots is 0.5117, for lot 1 = 0.9048, for lot 2 = 0.3451, and for lot 3 = 0.637. In all cases p-value is above the assumed significance level of 0.05. We fail to reject the null hypothesis.

# Study Design: MechaCar vs Competition.
# Electric vehicles and eco friendly  awareness are on the rise, customers are more cautious about pollution and car emissions. While many people cannot afford or won’t invest in the electric vehicle, MechaCar can provide a good alternative. I suggest testing for the following metrics to compare MechaCar against competition. A comparison of a single dependent variable exhaust system emissions means across a single independent variable transmission efficiency with multiple groups.
# H0: The means of exhaust system emissions of all groups are equal.
# Ha: The means of exhaust system emissions is different from all other groups.
# To test the hypotheses, I would use  Analysis of Variance.  Analysis of Variance  is used to test the means of a single dependent variable across a single independent variable with multiple groups. In the case of exhaust system emissions of different cars based on transmission efficiency. If we reject the null hypothesis, we can conclude that at least one of the means of exhaust system emissions is different from all other groups.
# In order to run this statistical test, we need the data from:
# vehicle ID
# exhaust system emissions data
# transmission efficiency data


