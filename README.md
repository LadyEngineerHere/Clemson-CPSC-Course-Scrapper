# Clemson CPSC Scrapper Jupyter Notebook

This Jupyter Notebook contains a Python script for scraping CPSC-related course information from Clemson University's catalog website.

## About

This Jupyter Notebook scrapes CPSC-related course information from Clemson University's catalog website. The motivation behind creating this program was to address the inconvenience of manually clicking through 15 pages on the catalog website to view the list of all CPSC courses offered. This script automates the process, making it easier to gather comprehensive course data efficiently.

## Features

- Utilizes the `requests` library for sending HTTP requests to the catalog website.
- Employs the `BeautifulSoup` library to parse the HTML content of the website.
- Utilizes the `pandas` library for data manipulation and exporting to Excel.
- Automatically saves the list of courses in an Excel file named `cpsc_related_data.xlsx`.

## Usage

1. Install Jupyter Notebook if you haven't already: pip install jupyter

2. Download the "clemson_CPSC_scrapper.ipyb" file to your local machine.

3. Open a terminal or command prompt and navigate to the directory where the notebook is located.

4. Run the Jupyter Notebook using the following command: jupyter notebook clemson_CPSC_scrapper.ipyb

5. Follow the instructions in the notebook to execute the Python code and scrape course data.

## Organized Data

I have manually organized the scraped data in Excel for better readability. You can find the organized results in the Excel file named `organized_cpsc_data.xlsx`.

## License

This Jupyter Notebook is provided under the [MIT License](LICENSE).

---

**Disclaimer:** This notebook is intended for educational and personal use. Use at your own discretion.


