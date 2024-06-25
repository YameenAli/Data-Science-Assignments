
# Assignment 9 

This repository contains solutions for Assignment 9, focusing on practical tasks related to Python programming and regular expressions. Below is a summary of what's included:

## Regular Expressions

Explored the use of regular expressions (regex) in Python for text processing tasks:
- Explained metacharacters and their significance in pattern matching.
- Developed scripts to validate email addresses and extract specific information from log files using regex patterns.

## Email Validation

Implemented a Python script to validate various email formats using regex, distinguishing between valid and invalid addresses.

## User Log Analysis

Developed a Python script to analyze log files:
- Extracted error messages and timestamps using regex patterns.
- Classified errors by severity (INFO, ERROR, WARNING) and generated a summary report.


## Web Scraping using Regular Expressions

This Python script `scrape_books.py` demonstrates how to scrape book information from a web page using regular expressions. It retrieves book titles and prices from the specified URL and stores the data in a JSON file for further analysis or processing.

## Overview

The script performs the following tasks:

1. **Scraping**: It uses the `requests` library to fetch the HTML content of a webpage.
2. **Regular Expressions**: Regular expressions (`re` module) are employed to extract:
   - Book titles using `<h3><a>` tags with specific attributes.
   - Book prices using `<p>` tags with a specific class attribute.
3. **Data Extraction**: After extracting titles and prices, it combines them into a list of dictionaries (`books`), where each dictionary represents a book with its title and price.
4. **Data Storage**: The scraped data (`books`) is then stored in a JSON file named `scraped_books.json` with proper formatting and encoding.

## Dependencies

- Python 3.x
- `requests` library (`pip install requests`)

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/book-scraping.git
   cd book-scraping


## Submission Details

- Submitted in PDF format with screenshots of code and outputs.
- Python scripts include comments explaining functionality and purpose of each step.
- Submitted to: jtechsolution93@gmail.com

Explore the repository for detailed scripts and examples showcasing the use of regular expressions in Python for various tasks.
