# BIOSTAT625 - Final Project Group 8

This is **WEEK 13**

The schedule rmd will be updated weekly, please check for any project updates.\
Please work on **individual coding files** whenever possible. **Merging** might fail.

## Data Processing: (100%)

1. Please turn all pre-processed datasets into CSV files, and upload the dataset and code to the folder "data_exploration". *(finished)* 

2. The processed whole data set is named as "housing_cleaned_price.csv", with price outliers deleted.
  
   The "housing_cleaned_Price+Carpet.csv" deleted the outliers for both carpet area and price.
   
   *p.s. the previous version of "housing_cleaned.csv" could could be reproduced with datasets within the Data section (remember to change the path before import the datasets) using Total_data.ipynb.*

3. The version of the cleaned datasets with location properly clustered by economic status and no outliers are stored in the "Data Exploration/housing_cleaned" folder
   
   1) **housing_cleaned_final.csv**
      
      path: Data Exploration/housing_cleaned/housing_cleaned_final.csv;
      
      Description: with missing values.
      
   2) file name **housing_rmna_cleaned_final.csv**

      path: Data Exploration/housing_cleaned/housing_rmna_cleaned_final.csv;

      Description: with no missing value.

      Special Reminder: The 'Transaction', 'Total Floors','location','State', 'Current Floor', 'Carpet Area' variables can be deleted when conducting the modeling process as they are either transformed to categorical variable or already conducted one-hot encoding and turned to other variables.

4. The final version (all categorical variable processed with one-hot encoding) of the datasets are stored in /Data Exploration:
   
   1) **final_OneHotEncoded_housing.csv**: without outliers deleted for price

      path: Data Exploration/final_OneHotEncoded_housing.csv;
  
   2) **final_rmna_OneHotEncoded_housing.csv**: without outliers deleted for price and no observations with missing values

       path: Data Exploration/final_rmna_OneHotEncoded_housing.csv;
      
   3) Will be updated: datasets with outliers

## Proposal: (100%)

Please find the final proposaln "Project Proposal_Final.pdf" in folder "Proposal Draft".

## Data Modeling: (0%)

Please upload the code and any related results to the "Data modeling" folder. 

## Final Report: (0%)

Please go to the same google drive folder for writing proposal.
