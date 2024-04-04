### QBD Book Scraper

This Python script is designed to scrape book details from the QBD Books website and store them in an Excel file.

## Features

Scraping: Utilizes requests, BeautifulSoup, and lxml libraries to scrape book details such as name, ISBN, authors, publication date, image source, price, number of pages, dimensions, and description from the QBD Books website.

Excel Export: Saves the scraped book details into an Excel file for further analysis or usage.

## Requirements

- 1.Python 3.x
- 2.openpyxl
- 3.requests
- 4.BeautifulSoup
- 5.lxml

## Usage

1.Clone the repository or download the script file directly.
2.Install the required libraries if not already installed:
  pip install openpyxl requests beautifulsoup4 lxml
3.Run the script qbd_book_scraper.py.
4.The script will scrape book details from the QBD Books website and save them into an Excel file named output.xlsx.
5.You can adjust the range of pages to scrape by modifying the total_page variable in the script.


## Script Overview
write_list_to_excel: Function to write a list of data to an Excel file. If the file doesn't exist, it creates a new Excel file with headers.
get_column: Function to get a column of data from an existing Excel file.
Main Loop: Iterates through a range of pages on the QBD Books website, scrapes book details, and writes them to an Excel file.


## Acknowledgments
This script was created as a learning exercise and may require updates or modifications to function with future changes to the QBD Books website structure.




