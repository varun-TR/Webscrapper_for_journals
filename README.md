# Webscrapper for journals

## 📰 Webscraper for Journals 📚
Welcome to the Webscraper for Journals project! This Python-based web scraping tool is designed to extract and organize information from journal websites, including abstracts, titles, authors, publish dates, DOI URLs, and affiliations.

## 🚀 Features
Scrape Journal Data: Extract titles, abstracts, authors, publish dates, and DOI URLs.
Data Storage: Save the scraped data in CSV and Excel formats.
Error Handling: Robust error handling for missing or inaccessible data.
Compatibility: Works with Chrome and chromedriver.

🛠️ Requirements
To run this project, you need to have the following Python packages installed:


pandas
selenium

You can install these packages using pip:

pip install  pandas selenium

🔧 Installation
Clone the Repository:

git clone https://github.com/yourusername/webscraper-for-journals.git
Navigate to the Project Directory:

cd webscraper-for-journals
Install Dependencies:

pip install -r requirements.txt
Download chromedriver:

Ensure you have the latest version of chromedriver that matches your Chrome browser. Place it in a directory included in your system PATH.

## ⚙️ Usage

Run the Script:

python webscraper.py
Output Files:

CSV File: output-final.csv - Contains the scraped data in CSV format.
Excel File: output-final.xlsx - Contains the scraped data in Excel format.

## View the Results:

The data includes:
Title: Title of the journal article
Authors: List of authors
Affiliations-ORCID IDs: Affiliations and ORCID IDs of authors
Publish Date: Date when the article was published
DOI URL: DOI URL of the article
Abstract: Abstract of the article

## 🚧 Error Handling
The script includes error handling for cases where abstracts or publish dates are missing. Error messages will be printed to the console if any issues occur.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing
Feel free to submit issues or pull requests. Your contributions are welcome!

