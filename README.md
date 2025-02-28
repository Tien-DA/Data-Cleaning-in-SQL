# Data Cleaning Project in SQL: Nashville Housing Dataset

## Project Overview

This project focuses on cleaning the "Nashville Housing" dataset using SQL. The primary objective was to address common data quality issues, such as inconsistent date formats, missing property information, and duplicated records. Several SQL queries were used to standardize the dataset, split combined fields, handle missing values, and ensure data consistency.

## Key Tasks and Techniques

1. **Standardizing Date Formats**: 
   - Converted the sale date to a consistent format using SQL `CONVERT()` function.

2. **Handling Missing Data**:
   - Updated missing property addresses by matching and filling null values from related records.

3. **Breaking Out Combined Fields**:
   - Split combined columns like `PropertyAddress` and `OwnerAddress` into individual components (e.g., address, city, state).

4. **Data Transformation**:
   - Changed "Y" and "N" values in the `SoldAsVacant` column to "Yes" and "No", respectively.

5. **Removing Duplicates**:
   - Applied `ROW_NUMBER()` to identify and remove duplicate records based on key fields.

6. **Dropping Unused Columns**:
   - Removed columns that were not necessary for the analysis using `ALTER TABLE` command.

7. **Importing Data (Advanced)**:
   - Provided methods to import the dataset using `BULK INSERT` and `OPENROWSET`.

## Key Skills and Tools Used

- **SQL**: For querying, cleaning, and transforming data.
- **Data Cleaning Techniques**: Standardization, missing value handling, and duplicate removal.
- **Data Transformation**: Splitting fields and updating categorical data.

## Setup Instructions

1. Clone this repository to your local machine:
2. Set up your SQL database and import the dataset using the SQL scripts provided in this repository.
3. Run the queries step by step to clean the dataset. The queries are structured in a way that they can be executed sequentially.
