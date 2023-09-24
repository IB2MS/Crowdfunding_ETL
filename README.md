# Crowdfunding_ETL Olesya, Darrick, Ruqayyah

# Project Outline 
## Background
This project requires building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After cleaning and transforming the data, you will create *four* CSV files and use the CSV file data to create and *ERD and a table schema*. Finally, you will upload the CSV file data into a *Postgres database*.

These are the major components:
- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database

### Create the Category and Subcategory DataFrames
1. Extract and transform the crowdunding.xlsx Excel data to create a category DataFrame that has the following columns:
    - A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is         the number of unique categories
    - A "category" column that contains only the category titles
2. Export the category DataFrame as category.csv and save it to your GitHub repository.
3. Extract and transform the crowdfunding.xlsx Excel data to create a subcategory DataFrame that has the following columns:
     - A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn",             where n is the number of unique subcategories
     - A "subcategory" column that contains only the subcategory titles
     - 
