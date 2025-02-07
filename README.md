# Web Scraper for Largest U.S. Companies by Revenue

This repository contains a Python script that scrapes data from Wikipedia about the largest companies in the United States by revenue. The script extracts table data and saves it into a CSV file.

## Features
- Uses `BeautifulSoup` to scrape a table from Wikipedia.
- Extracts company data and stores it in a Pandas DataFrame.
- Saves the data as a CSV file for further analysis.

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install requests beautifulsoup4 pandas
```

## Usage
Run the script to scrape the latest data from Wikipedia and save it as a CSV file:
```bash
python scraper.py
```
