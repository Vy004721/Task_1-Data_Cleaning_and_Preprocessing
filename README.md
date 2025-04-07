# Task_1-Data_Cleaning_and_Preprocessing

Netflix Titles Dataset Cleaning (Excel)

This project involves cleaning the netflix_titles.csv dataset using Microsoft Excel. Below is a summary of all the preprocessing steps performed to ensure the dataset is clean and ready for analysis.

Data Cleaning Steps

Missing Values
Used filters and Go To Special > Blanks to identify missing values.
Filled missing director values with "Unknown".
Dropped rows with missing essential fields like title using filters.
Removed Duplicates
Applied Data > Remove Duplicates across all columns to eliminate exact duplicate rows.
Standardized Text Values
Used =PROPER(TRIM(A2)) to clean and standardize fields like type and country.
Removed extra spaces and ensured consistent capitalization.
Converted Date Formats
Formatted date_added to a consistent dd-mm-yyyy format using Excel’s Custom Format or =TEXT() formula.
Cleaned Column Headers
Renamed column headers to be:
All lowercase
Spaces replaced with underscores
Example: Show ID → show_id, Date Added → date_added
Fixed Data Types
Extracted numeric values from duration using.
