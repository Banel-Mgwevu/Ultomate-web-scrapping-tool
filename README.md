
---

# Web Scraper

This is a simple web scraper that downloads and saves resources (CSS, JavaScript, images, and fonts) from a specified webpage. The HTML content of the webpage is also saved locally.

## Features

- Downloads CSS files
- Downloads JavaScript files
- Downloads image files
- Downloads font files
- Saves the HTML content of the page

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Installation

1. Clone the repository or download the script.

2. Install the required Python packages using pip:
   ```bash
   pip install requests beautifulsoup4
   ```

## Usage

1. Edit the script to change the URL of the webpage you want to scrape:
   ```python
   # URL of the webpage to scrape
   url = "https://www.EXAMPLE.com/"
   ```

2. Run the script:
   ```bash
   python scrape_page.py
   ```

3. The scraped resources will be saved in a folder named `scraped_data` in the same directory as the script.

## Files

- `scrape_page.py`: The main script file containing the web scraping logic.
- `scraped_data/`: The directory where all the downloaded resources and HTML content will be saved.

## Functions

### `download_resource(url, save_folder)`
Downloads a resource from the given URL and saves it to the specified folder.

- `url`: The URL of the resource to download.
- `save_folder`: The folder where the downloaded resource will be saved.

### `scrape_page(url)`
Scrapes the webpage at the given URL and downloads all CSS, JavaScript, image, and font files, saving them locally.

- `url`: The URL of the webpage to scrape.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improving this script.

## Author

[Banele MGWEVU]
---

