# Amazon-ASIN-JSON-Generator

This script creates a GUI using `tkinter` to generate and display a JSON object based on a list of Amazon Standard Identification Numbers (ASINs) provided by the user. It is specifically designed to create JSON formatted for use with the Chrome extension "Web Scraper - Free Web Scraping," which automates data extraction from web pages.

After downloading and installing the extension, and running the `Amazon ASIN JSON Generator` for the desired ASINs to get your JSON, follow these steps:

1. Open the Web Scraper by right-clicking on a web page, selecting "Inspect," and navigating to the "Web Scraper" tab.
2. Click Create a new sitemap and select import sitemap.
3. Paste the generated JSON into the sitemap section and give it a name.
4. Lastly, launch the scraper and once it's completed, export the scraped data.

Depending on the departments, deals, availability, and other factors, you may need to modify json_data to return the specific page elements you want to extract.

An example csv of the exported results is included in this repo for the following ASINs:
B08S473TPS
B08S48BKGQ
B08S4646QQ
B09JTQ2YFP
