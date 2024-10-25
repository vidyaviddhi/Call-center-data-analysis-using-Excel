# Content Category Popularity Analysis

This project analyzes content category popularity to identify the top 5 categories with the highest popularity scores, based on a dataset of reaction types and scores. 
Following data cleaning and merging steps, a single dataset is created to perform the analysis. 
This project is part of a larger data-driven initiative to help clients better understand their content impact.

## Process Outline
### Data Selection and Cleaning:

Selected three relevant datasets based on required fields: content ID, category, content type, reaction type, and reaction score.
Cleaned each dataset by:  

Removing rows with missing values.  

Adjusting data types for accurate calculations.  

Dropping irrelevant columns to focus on necessary data.  

### Data Merging:

Used the Reaction table as the base.  

Merged columns from Content and Reaction Types tables using VLOOKUP.  

Resulted in a comprehensive dataset for popularity analysis.  

### Popularity Analysis:

Calculated total popularity scores for each category using the SUMIF formula.  

Ranked categories to identify the top 5 with the highest scores.  

## Final Output
Cleaned Dataset: Combined and prepped for analysis.  

Top 5 Categories: Identified categories with the largest popularity based on reaction scores.  
