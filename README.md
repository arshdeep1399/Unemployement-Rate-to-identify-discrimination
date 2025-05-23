In this project we will try to identify the discrimination in Unemployment-Rate based on of Race, Gender and location.


**Gathering the dataset :**

- The dataset was extracted from FRED gov website - Financial Reserve Bank of St. Louis (FRED) which Collects economic data.
- Fred API was used to populate pandas dataframe.

**Statistical Analysis :**

We used methods from scipy.stats to conduct various statistical tests
- First, we tested if the unemployment rates were normally distributed using a Shapiro-Wilk Test

Seasonally Adjusted-
ShapiroResult(statistic=0.95, pvalue=2.67e-16)

Not Seasonally Adjusted-
ShapiroResult(statistic=0.96, pvalue=4.92e-15)

- Result: Cannot assume normal distribution


**GUI Tkinter -**


- Provides a personalized result for unique comparisons
- GUI window allows users to select Years and States
- Users can select as many years or states as they wish
- Tkinter library was utilized to achieve this GUI task
- Results in graphs plotted according to user’s input
- Axis will be adjusted automatically according to the selection criteria


**Conclusion -**

Discrimination appears to be present based on variation of unemployment rates
- Sex: Women experience a higher mean rate of unemployment
- Race: Black and Hispanic citizens experience a higher unemployment rate than White
- Location: states experience differing levels of mean unemployment rates

New discoveries in our findings
- Not all states are equally impacted during the same year
- The mean is just that - Doesn’t accurately represent a group within our data
