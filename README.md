# Internal Work Website Data Extraction Tool

This Python script automates the process of retrieving product information for products from the [brands.silo.co.za] website and populating an Excel file with the gathered data.

## Overview

This script is designed to simplify the retrieval of in-house product data from a web-based work platform. It facilitates the process by using Selenium to simulate user actions, such as searching for products and extracting relevant information. The extracted data is then organized and saved in an Excel file for easy access and analysis.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/revlon-web-scraper.git
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Download and install the appropriate ChromeDriver using `webdriver_manager`.

## Usage

1. Ensure you have Python installed.
2. Run the script `revlon_scraper.py`.
3. The script will launch a Chrome browser and perform the automated scraping process.
4. The extracted data will be saved in an Excel file named `Revlon.xlsx`.

## Features

- Automated web scraping of product information for a predefined list of Revlon products.
- Extraction of barcode numbers, brand names, descriptions, and dimensional data.
- Data is saved in an Excel file for easy access and analysis.
