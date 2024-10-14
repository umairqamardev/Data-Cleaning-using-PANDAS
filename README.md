# Data-Cleaning-using-PANDAS

Overview

This project focuses on cleaning and preprocessing the "Customer Call List.xlsx" dataset using Pandas in Python within a Jupyter Notebook environment. The aim is to ensure that the data is clean, structured, and ready for analysis.

Dataset
File Name: Customer Call List.xlsx

Key Columns:
Address: Contains street address, state, and ZIP code.
Last_Name: May contain unwanted characters.
Phone_Number: May have various formats and incomplete data.
Do_Not_Contact: Indicates customer contact preference.
Data Cleaning Steps

Removing Duplicates: Used drop_duplicates() to eliminate duplicate entries.
Dropping Unnecessary Columns: Removed the Not_Useful_Column.
Cleaning Text Fields: Stripped unwanted characters from Last_Name and replaced incomplete phone numbers.
Splitting Address: Divided Address into Street_Address, State, and Zip_Code.
Handling Missing Values: Filled NaN with empty strings.
Removing Opt-out Contacts: Dropped rows marked as Y in Do_Not_Contact and empty phone numbers.
Resetting Index: Adjusted the DataFrame index post-cleaning.
