# College_Work_webscraping

## Description

This repository contains a Python script that processes contact data extracted from HTML tables. The script performs the following operations:

1. **Data Extraction**: Extracts company and contact details from HTML.
2. **Data Cleaning**: Separates company names and locations, as well as websites and email addresses.
3. **Data Reorganization**: Moves the first column of a DataFrame to the last position.
4. **Data Export**: Saves the cleaned data to a CSV file.

## Installation

To get started, clone this repository and install the required packages:

```
git clone https://github.com/your-username/contact-data-processing.git
```

# Requirements
Python 3.x
Pandas
Requests (if web scraping is involved)
BeautifulSoup (if web scraping is involved)
# Usage
Extracting Data: Modify the script to fetch data from your HTML source.

Processing Data: The script will handle the following:

Extracting and cleaning contact information.
Reordering DataFrame columns.
Saving Data: The cleaned data will be saved to Company_detail.csv.

# Difficulties Faced
Handling Mixed Formats: Extracting contact information from strings with varying formats (e.g., missing spaces between website and email) was challenging. The use of regular expressions helped to address this issue.

Column Reordering: Reordering DataFrame columns required careful handling to ensure that the first column was correctly moved to the end.

Error Handling: Encountered issues with AttributeError and IndexError during DataFrame operations, which were resolved by checking data types and refining the extraction logic.

# Things Learned
Regular Expressions: Gained experience in using regular expressions to handle complex string formats and extract relevant data.

DataFrame Operations: Improved skills in manipulating and reordering DataFrame columns using pandas.

Error Handling: Enhanced ability to debug and handle various types of errors in Python, especially related to data processing and extraction.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.
