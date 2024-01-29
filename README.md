# Dollar Value Consultation Script

## Overview
This Python script automates the process of fetching the current exchange rates for the US Dollar and Uruguayan Pesos. Utilizing Selenium for web scraping and PyAutoGUI for automation, the script navigates to Google, performs searches to find the latest exchange rates, and saves these values in an Excel spreadsheet. This tool is particularly useful for financial analysts, travelers, or anyone needing up-to-date currency exchange information.

## Features
- **Automated Web Scraping**: Fetches the latest exchange rates for USD and Uruguayan Pesos using Google search.
- **Excel Integration**: Writes the fetched exchange rates to an Excel file, allowing for easy record-keeping and further analysis.
- **User-Friendly**: Automatically opens the Excel file with the fetched data for immediate viewing.

## Prerequisites
To run this script, you need to have the following installed:
- Python 3.x
- Selenium WebDriver
- PyAutoGUI
- XlsxWriter
- A WebDriver compatible with your preferred browser (e.g., EdgeDriver for Microsoft Edge)

Ensure that Python and pip are correctly installed on your system. You can verify this by running `python --version` and `pip --version` in your terminal or command prompt.

## Installation
1. Clone the repository or download the script to your local machine.
2. Install the required Python packages using pip:
 pip install selenium pyautogui xlsxwriter

3. Download and install the appropriate WebDriver for the browser you intend to use. Place the WebDriver in a location recognized by your system's PATH environment variable or specify its location directly in the script.

## Usage
1. Update the `urlArchivo` variable in the script to the desired path where the Excel file should be saved.
2. Run the script using Python:

python script_name.py

3. The script will automatically open the specified browser, navigate to Google, perform the searches, extract the exchange rates, save them to an Excel file, and then open this file for you to view.

## Customization
- **Browser Selection**: Modify the script to use a different browser by changing the WebDriver instance.
- **Exchange Rates**: To fetch different currencies, adjust the search queries within the script accordingly.
- **Excel File Location**: Change the `urlArchivo` variable to save the Excel file in a different location.

## Known Issues
- The script may fail if the structure of the Google search results page changes or if the XPath selectors become outdated.
- Performance may vary based on internet speed and system capabilities.

## Contributing
Contributions to improve the script or add new features are welcome. Please open an issue or pull request on the repository.

## License
This script is provided "as is", without warranty of any kind. Feel free to use and modify it for your personal or professional projects.

