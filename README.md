# AI Web Scraper

This AI Web Scraper is a Python-based tool designed to automate data extraction from web pages. It uses web scraping techniques with `selenium` to gather information, parse the data, and process it for analytical purposes. This repository provides a set of scripts that simplify the scraping process and output structured data.

## Features

- **Automated Web Navigation**: Uses `selenium` and `chromedriver` to navigate and scrape dynamically-loaded content.
- **Data Parsing**: Extracts relevant information from HTML structures using customizable parsing functions.
- **Data Processing**: Stores and formats extracted data for further analysis.

## Requirements

- Python 3.x
- ChromeDriver compatible with your Chrome browser version

Install dependencies by running:
```bash
pip install -r requirements.txt
```
## Setup
1. Create a Bright Data Account:

    - Sign up at Bright Data and navigate to Proxies and Scraping.
    - Click Add and select Scraping Browser.
    - Change the Zone Name as desired.
    - Copy the generated Selenium URL.
2. Configure Environment Variables:

    - Create a .env file in the project root.
    - Add the following line with your Selenium URL:
```bash
WEBDRIVER="YOUR_SELENIUM_URL"
```
## Files
 - main.py: Main script to execute the web scraper.
 - scrape.py: Contains scraping functions to fetch data.
 - parse.py: Parsing functions to filter and structure data.

## Usage
1. Clone the repository:

```bash
git clone https://github.com/nijgururajofficial/ai_web_scraper.git
cd ai_web_scraper
```
2. Run the main script:

```bash
streamlit run main.py
```
Customize scrape.py and parse.py to adapt the scraper to different websites.