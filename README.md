# Accounting Automation

## Overview

This repository houses a Python script designed to automate the process of entering company information into a web application. The script utilizes Selenium WebDriver to interact with the web interface, fetches company details from an Excel spreadsheet, and populates the corresponding fields on the website's form.

## Features

- **Efficient Data Entry:** Eliminates manual data entry tasks, saving time and reducing errors.\
- **Integration with Excel**: Fetches company information from an Excel file for seamless integration.\
- **Customization**: Easily adaptable for different websites and forms by modifying XPath selectors and data sources.\
- **Sleep Timers**: Includes sleep timers to ensure proper page loading and element visibility, enhancing reliability.

## Requirements

- Python 3.x
- Selenium WebDriver
- Chrome WebDriver
- Openpyxl
- Google Chrome

## Setup Instructions

1. Install Python 3.x from python.org.
2. Install Selenium WebDriver using pip:
```bash
pip install selenium
```
3. Download Chrome WebDriver from ChromeDriver Downloads and place it in your system's PATH.
4. Install Openpyxl using pip:
```bash
pip install openpyxl
```
5. Clone this repository:

```bash
git clone <repository_url>
```
6. Ensure the empresas.xlsx file containing company information is present in the project directory.

## Usage

1. Open the Python script (data_entry_automation.py) in a text editor.
2. Modify the script according to your web application's structure and the Excel file's format if necessary.
3. Run the script:
```bash
python data_entry_automation.py
```
4. Sit back and let the automation handle the data entry process.

## Notes

- Ensure the Chrome WebDriver version matches your installed Chrome browser version.
- Adjust sleep timers as needed based on the website's responsiveness.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
