# Grainger Web Scraper

A Python-based web scraping tool designed to extract product information from Grainger and save it into a structured CSV format.

## 📂 Repository Structure

* `Grainger_webscrape.ipynb`: The main Jupyter Notebook containing the scraping logic, data processing, and export functions.
* `producst.csv`: The output file containing the scraped data (Note: likely intended to be named `products.csv`).

## 🚀 Features

* **Automated Scraping**: Fetches product details from the Grainger website.
* **Data Extraction**: Parses key product information (likely names, prices, specifications, etc.).
* **CSV Export**: Saves the collected data locally for further analysis or usage.

## 🛠️ Prerequisites

To run this project, you need **Python** installed along with a way to run Jupyter Notebooks (like Anaconda, VS Code, or JupyterLab).

You will likely need the following Python libraries installed. You can install them via pip:

```bash
pip install pandas beautifulsoup4 requests

```

*(Note: If you used Selenium or Playwright in your code, please add `selenium` or `playwright` to this list.)*

## 📖 How to Use

1. **Clone the Repository:**
```bash
git clone https://github.com/Sooryavenkat/Grainger_website__webscraping.git
cd Grainger_webscraping

```


2. **Launch Jupyter Notebook:**
```bash
jupyter notebook

```


3. **Run the Scraper:**
* Open `Grainger_webscrape.ipynb`.
* Run the cells sequentially to start the scraping process.
* The script will generate the output file `producst.csv` in the same directory.



## ⚠️ Disclaimer

This tool is for educational purposes only. Web scraping should be done responsibly and in accordance with the target website's `robots.txt` file and Terms of Service.
