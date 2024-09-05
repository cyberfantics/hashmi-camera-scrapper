# Hashmi Cameras Product Scraper

This Python script scrapes product information from the Hashmi Cameras website, including product names, prices, links, and categories. The data is extracted using BeautifulSoup and saved into a CSV file for further analysis.

## Features

- Scrapes product names, URLs, prices, and categories from multiple pages of the Hashmi Cameras website.
- Saves the scraped data into a CSV file (`products.csv`).
- Handles pagination and processes multiple pages to gather comprehensive product data.

## Prerequisites

- Python 3.x
- Required Python packages (install via `pip`):
  - `requests`
  - `beautifulsoup4`
  - `pandas`

You can install the required packages with the following command:

```bash
pip install requests beautifulsoup4 pandas
```

## Usage
1) Clone the repository and navigate to the project directory:
  ``` git clone https://github.com/CyberFantics/hashmi-cameras-scraper.git
      cd hashmi-cameras-scraper
  ```

2) Run the scraper:
   ```
    python hashmi_cameras_scraper.py
   ```
   
The scraped data will be saved in the `products.csv` file.

## Notes
- The script includes basic error handling for failed page requests.
- Ensure that the HTML structure of the website remains consistent, as changes may require modifications to the scraper logic.



