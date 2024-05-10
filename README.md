# SRCC-Project

This repository hosts my project on regression analysis of police use of force data from Chicago, Seattle, and New Orleans. It looks at race as a possible predictor of force level and discusses the results.

# Description 
Logistic regression was used with a basic train/test split (test size = 0.33) of each data set. A confusion matrix was used to compare the predicted versus test set. Overall, racial variables could be used to predict the level of force used with 53.2% accuracy in Chicago, 77.4% accuracy in Seattle, and 69.3% accuracy in New Orleans. Further comparisons with other categorical variables (such as gender and age), environmental factors, or numerical demographic population data may be analyzed in the future as well. The results are discussed with visualizations of teh distribution of race in high-level force incidents in each city.

# Requirements
This project utilizes open source data, Google Colab IDE, and scikit-learn, pandas, and altair libraries.

# Data
The data used in this project is open source from each city's website. These cities were chosen in large part because of the organization and legibility of their data. Data from only the most recent year in each set were used. All data set CSVs may be found in the main branch folder.

# Data processing
A significant amount of processing was done to clean the data set, given that inconsistencies in data is a significant issue in measuring police statistics. Columns from the original CSVs were narrowed down to relevant and consistent data.

# Authors
This project and corresponding repository was created by Genny Sheara and presented at the 2024 Student Research and Creativity Conference at Seattle University. LinkedIn: https://www.linkedin.com/in/genny-sheara/

# License
All data and tools used in this project are open source and reproducible by anyone.
