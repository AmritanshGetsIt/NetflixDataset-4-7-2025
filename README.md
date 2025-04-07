# NetflixDataset-4-7-2025
Initial Observations:
Missing values: director, cast, country, date_added, rating, and duration have null values.
Duplicates: Not yet checked.
Inconsistent text formatting: Country names, ratings, and genres might need standardization.
Date format: date_added is in "Month Day, Year" format; it should be converted to a consistent YYYY-MM-DD format.
Column names: They contain spaces and uppercase letters, which should be cleaned.
Data types: date_added should be converted to datetime.

Data Cleaning Summary:
Total Rows (After Cleaning): 8,807
Missing Values Handled: Filled missing values in director, cast, country, date_added, rating, and duration with appropriate placeholders.
Duplicates Removed: Yes
Text Standardized: Standardized type, country, rating, and listed_in fields.
Date Format Standardized: Converted date_added to YYYY-MM-DD.
Column Names Cleaned: Renamed to lowercase with underscores for uniformity.
Data Types Fixed: release_year set as int, date_added converted to datetime.
