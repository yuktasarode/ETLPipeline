# ETL Pipeline with AWS and Python

This mini-project is focused on building an end-to-end ETL pipeline. The stages are as follows:

<ins>Extract</ins>
- Extracted data from CSV file
- Used pandas utlities to describe data

<ins>Transform</ins>
- Removed unwanted columns
- Filling empty cells
- Populating columns (peer dependence)
- Removing rows with empty cells
- Maintaining a single data type 
- Rounding functions and type casting
- Denormalize cell modification

<ins>Load</ins>
- Loaded transformed data into Redshift to get insights (quick sight and Matplotllib)
- Loaded data frame into S3

