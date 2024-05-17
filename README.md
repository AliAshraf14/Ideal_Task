# Web Scraping Books Information

This project involves scraping book titles and descriptions from a website and storing the data in a JSON file using Selenium.

## Approach

1. **Setup and Initialization**:
   - Install Selenium and `webdriver_manager`.
   - Initialize the Chrome WebDriver using `webdriver_manager`.

2. **Open the Website**:
   - Define the URL of the website to scrape.
   - Open the website using the WebDriver.

3. **Scrape the Data**:
   - Allow some time for the page to fully load.
   - Use Selenium to find the elements containing book titles and descriptions by their respective class names.
   - Store the titles and descriptions in a dictionary where the title is the key and the description is the value.

4. **Save Data to JSON**:
   - Convert the dictionary to a JSON file using Python's `json` module.
   - Save the JSON file to the current directory.

## File Summary

- `Ideall Task.ipynb`: The main script that performs the web scraping and saves the data to a JSON file.
- `books.json`: The output JSON file containing the scraped book titles and descriptions.

## Requirements

- Selenium
- `webdriver_manager`
- Google Chrome

## Usage

1. Ensure all required packages are installed.
2. Run `Ideall Task.ipynb` to scrape the data and generate `books.json`.

