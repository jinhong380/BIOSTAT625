# BIOSTAT625 - Final Project Group 7

## Data Exploratoin:
Dataset initial exploration and pre-processings:

1. Code: store all codes for specific covariate transformation/ recategorization/ and one hot encoding. Clustering folder is specifically used for handling location variable.

2. Individual_data stores all results collected from pre-processing.

3. The final version (all categorical variable processed with one-hot encoding) of the datasets are stored in /Data Exploration:
   
   1) **final_OneHotEncoded_housing.csv**: without outliers deleted for price

      path: Data Exploration/final_OneHotEncoded_housing.csv;
  
   2) **final_rmna_OneHotEncoded_housing.csv**: without outliers deleted for price and no observations with missing values

       path: Data Exploration/final_rmna_OneHotEncoded_housing.csv;
      
   3) **final_full_OneHotEncoded_housing.csv**: with no outliers deleted
  
      path: Data Exploration/final_full_OneHotEncoded_housing.csv;
      
   4) **final_full_rmna_OneHotEncoded_housing.csv**: with no outliers deleted and no observations with missing values
  
      path: Data Exploration/final_full_rmna_OneHotEncoded_housing.csv;

## Data Modeling:

Contains the code and output for both elastic net and lightGBM approach. For the lightGBM folder, each dataset used was separated into a single document with corresponding result.

## Final Report:

Contains the graph used for report writing and the report RMD file.

## Other:

Weekly meeting information recorded in schedule; challenges record the difficulties we met during in this project.

