# CS131-DiabetesProject
CS131 Project Repository


**Project Title:**
Diabetes risk factor analysis

**Authors:**
Thaneesha Singh

**Project Description:**
Using the Behavioral Risk Factor Surveillance System dataset from Kaggle, that provides data on 400000 people from 2011 to 2015, I want to associate particular risk factors with a diabetes diagnosis. The general dataset provides information on different health practices and behaviors that are linked to different chronic disease (not just diabetes), but I plan on cleaning and filtering this dataset to match my goals. I hope to find particular "strong" and "weak" risk factors for diabetes and how a diagnosis varies by other numerical factors (age, weight, etc.). The project will have a variety of visualizations using matplotlib and seaborn, such as histogram, heat maps, etc. Lastly, my data analysis and visualization will create a clear "story", so audiences can relate my findings to their own life and understand if they are at risk for such a disease. 

**Project Outline/Plan:**
1. Data Collection & Storage - Use Kaggle Dataset - https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system/data
  Data is quite large - 748 MB, 400000 people
  Need to make sure that when loading in this dataset, I only select relevant columns to diabetes, risk factors, and preventative health practices.
  Store the data in a Pandas Data Frame.
2. Data Cleaning -
   Check for any null rows, remove or impute depending on scenario.
   Make sure that columns are the correct datatype. 
   Many columns have data in a message (as some values were obtained as sentences from a phone call) -- meaning, I need to standardize the columns.
   Check for outliers in the numerical (age, weight, etc.).
   They made binary values 1 and 2 (not 0 and 1) - can change to proper binary values.
4. Data Analysis -
   Will make summary statistics of different columns, using groupBy operations to get narrower results of particular categories.
   Understand the distribution of different numerical columns, test certain alternative hypothesis of relationships with accurate tests.
   Make correlation matrixes to see strongest relationships between the data.
5. Data Visualization
   Make histograms, bar plots, box and whisker plots, scatter plots to get a general understanding of data.
   Use seaborn to make more narrow and specialized plots, particularly, heatmaps, density graphs, pie charts, etc.


Note - more specialized plot types and data analysis techniques will become more clear as I begin to work on the data (will correlate with the project deadlines provided in class). 
