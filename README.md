# NCAA-March-Madness

## Project 4 Assignment

# Overview
The purpose of this analysis was to obtain greater understanding of NCAA Division 1 Statistics using Machine Learning. Can we predict tournament contestants based on historical data?
  
### Datasets Analyzed 
   * The main dataset used was several data pulls of team stats going back 10 to 20 years, and included such stats as Assist/Turnover Ratio, Three-Point Attempts, and Rebounds. These were all pulled from the stats page of the NCAA website and combined into one main csv file using Spark. The combined data then includes Team Name, Season of the Stats in format of 1011 for example, meaning years 2010 through 2011. Overall, about 3700 records combined to analyze.

# References for the data source(s)
*NCAA Mens Basketball Division 1 statistics - https://stats.ncaa.org/rankings/change_sport_year_div

# References for any code used that is not your own

Requirements
# Data Model Implementation.
-A Python script initializes, trains, and evaluates a model: All our models were run in Python scripts (see 'Madness Logistic Regression.ipynb', 'Madness KNN.ipynb' and 'Madness Random Forest.ipynb')

-The data is cleaned, normalized, and standardized prior to modeling: Yes. Most of our time went to wrangling, combining, cleaning and joining various sets of data (If interested, see directories within "Resources" directory)

-The model utilizes data retrieved from SQL or Spark: Yes. For work, please see 'SparkCombine.ipynb' within the directory 'Merged Data' within the directory 'Resources'.

-The model demonstrates meaningful predictive power at least 75% classification accuracy or 0.80 R-squared: Yes. Our logistic regression model was able to achieve 75% accuracy after several optimization attempts.

# Data Model Optimization
-The model optimization and evaluation process showing iterative changes made to the model and the resulting changes in model performance is documented in either a CSV/Excel table or in the Python script itself: Yes. Core iterations as well as the resulting changes are printed within each model notebook.

-Overall model performance is printed or displayed at the end of the script: Yes. Core iterations as well as the resulting changes are printed within each model notebook.

# GitHub Documentation
-GitHub repository is free of unnecessary files and folders and has an appropriate .gitignore in use: The only files in the main repo should be the three model notebooks and the presentation PDF. The only standalone CSV within 'Resources' is the master data sheet. We also inclued individual pieces of data and the code we used to wrangle/combine it all within the 'Individual Stats', 'Madness_data' and 'Merged Data' directories. 

-The README is customized as a polished presentation of the content of the project: Yes, by following this ReadMe, all content contained in the repo for this project should be understood and easy to navigate to.

# Group Presentation
-All group members speak during the presentation: Yes

-Content, transitions, and conclusions flow smoothly within any time restrictions: Mostly, although we were missing our model content

-The content is relevant to the project: Partially, as model content was missing during group presentation

-The presentation maintains audience interest: You tell us!
