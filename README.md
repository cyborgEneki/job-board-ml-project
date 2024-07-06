# Python Script for Scraping a Public Job Board

## Overview
This Python script scrapes job postings from a public job board and prepares the data for a machine learning project. It utilizes web scraping techniques to extract job titles, links, descriptions, and date posted from the job board's HTML structure.

## Features
- **Scraping Job Postings**: Uses BeautifulSoup library to parse HTML and extract job details.
- **Data Cleaning**: Handles text cleaning tasks such as removing HTML tags and formatting text.
- **Data Structuring**: Organizes extracted data into a structured format using pandas DataFrame.
- **CSV Export**: Saves the scraped data into a CSV file for further analysis or machine learning model training.

## Character Limitation
- The data in the 'Content' column has been limited to a maximum of 10000 characters.

## Libraries Used
- **BeautifulSoup**: For parsing HTML and navigating the DOM tree of the job board.
- **pandas**: For data manipulation and structuring the scraped data into a DataFrame.
- **requests**: For making HTTP requests to fetch the HTML content of the job board.

## Workflow
1. **Fetch HTML Content**: Utilizes the `requests` library to retrieve the HTML content of the job board page.
2. **Parse HTML**: Uses BeautifulSoup to parse the HTML content and extract relevant job details.
3. **Data Extraction**: Extracts job titles, links, descriptions, and date posted from the parsed HTML.
4. **Data Cleaning**: Cleans extracted text data, such as removing unnecessary HTML tags, newline characters, or extra spaces.
5. **Data Structuring**: Constructs a pandas DataFrame to store the cleaned and structured job data.
6. **CSV Export**: Saves the DataFrame to a CSV file, ensuring all data is properly formatted and ready for analysis or machine learning tasks.
