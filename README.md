# Crowdfunding-ETL
## Module 13 - Project 2

-------
## Overview
* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database

--------
## DataFrames
### Category DF (Jacque)
* The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories (5 points)
* The DataFrame has a "category" column that contains only the category titles (5 points)
* The category DataFrame is exported as category.csv (5 points)

### Subcategory DF (Amy)
* The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories (5 points)
* The DataFrame contains a "subcategory" column that contains only the subcategory titles (5 points)
* The subcategory DataFrame is exported as subcategory.csv (5 points)

### Campaign DF (Jacque)
* The DataFrame has the following columns: (25 points)
   * A "cf_id" column
   * A "contact_id" column
   * A "company_name" column
   * A "description" column
   * A "goal" column that is a float data type
   * A "pledged" column that is a float data type
   * An "outcome" column
   * A "backers_count" column
   * A "country" column
   * A "currency" column
   * A "launch_date" with the time formatted as "YYYY-MM-DD"
   * An "end_date" with the time formatted as "YYYY-MM-DD"
   * A "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
   * A "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
* The campaign DataFrame is exported as campaign.csv (5 points)

### Contacts DF (Amy)
* The DataFrame has the following columns: (10 points)
* A "contact_id" column
* A "first_name" column
* A "last_name" column
* An "email" column
* The contacts DataFrame is exported as contacts.csv (5 points)

---------
## Database (Jacque and Amy)
* A database schema labeled, crowdfunding_db_schema.sql is created (5 points)
* A crowdfunding_db is created using the crowdfunding_db_schema.sql file (5 points)
* The database has the appropriate primary and foreign keys and relationships (5 points)
* Each CSV file is imported into the appropriate table without errors (5 points)
* The data from each table is displayed using a SELECT * statement (5 points)

-------
## Summary

--------
## References and Sources