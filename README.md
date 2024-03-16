# Website_Scraper
 A Scraper that logs into a website, collects product names and images, converts images to a computer-readable format, and saves all details to an Excel file before closing the browser.

# Product Information Scraper

This repository contains an automated Python script that logs into a specific staging website and scrapes product information, including names and associated images. It also converts the images to a binary format and compiles all the collected data into an Excel spreadsheet for easy analysis and reference.

## Prerequisites

Before running the script, ensure you have Python and the following packages installed:
- Selenium
- openpyxl
- webdriver-manager

These can be installed via pip with the command:

## Setup

To run this script, you need Python installed on your machine along with Selenium and openpyxl packages. You can install the necessary packages using:


```bash
pip install selenium openpyxl webdriver-manager
```


## Configuration

Update the `product_scraper.py` script with your actual credentials for the staging website by replacing `'gmail.com'` with your login email and `'yourpassword'` with your password.

## Running the Script

Navigate to the repository directory and run the script using:
```bash
python Website_scraper_Images.ipynb

```


## Output

Upon successful execution, the script generates an Excel file titled `products_images.xlsx`. This file contains the following columns:
- Product Name
- Image Name
- Image URL
- Image in Binary

## Contributing

Contributions to enhance the functionality of this script are welcome. Please feel free to fork the repository and submit a pull request.


## Author

- [Farheen Latif](farheenlatif8@gmail.com)

## Acknowledgments

This script was created for educational purposes and is not intended for commercial use without explicit permission from the website owners.

## Disclaimer

The use of web scraping techniques may be subject to legal and privacy considerations. Ensure you have permission to scrape the data and are compliant with any terms of service and laws that apply.

