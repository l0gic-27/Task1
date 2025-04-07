# Task1

📊 Netflix Titles Dataset Cleaning
This project involves cleaning the Netflix Titles Dataset using Python and Pandas in Google Colab. The dataset includes information about movies and TV shows available on Netflix.

✅ Data Cleaning Steps Performed
File Upload and Reading

Uploaded the CSV file (netflix_titles.csv) and loaded it into a Pandas DataFrame.

Handling Missing Values

Identified missing data using .isnull().sum().

Removed rows with missing title values (since they are essential).

Filled other missing values (like director, cast, country, etc.) with 'Unknown'.

Removing Duplicates

Removed duplicate records using .drop_duplicates() to ensure data integrity.

Standardizing Text Values

Cleaned and standardized textual fields (e.g., country names, types, ratings) using string methods (.str.strip(), .str.title(), .str.upper()).

Date Format Conversion

Converted date_added to a consistent format (dd-mm-yyyy) using pd.to_datetime() and .dt.strftime().

Renaming Columns

Made column headers lowercase and replaced spaces with underscores for easier referencing in code.

Fixing Data Types

Ensured release_year is treated as an integer.

Converted date_added to proper datetime format.

Exporting Cleaned Data

Saved the cleaned dataset to a new CSV file (netflix_cleaned.csv) for further analysis or use.

🔧 Tools Used
Python

Pandas

Google Colab
