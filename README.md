<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/User_icon_2.svg" width="30%" alt="Webscraping Project Logo"/>

# WEBSCRAPING PROJECT

<em>A Python project that scrapes structured data from a sample webpage and exports it to CSV and JSON files.</em>

<!-- BADGES -->
![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Libraries](https://img.shields.io/badge/Libraries-requests%2C%20beautifulsoup4%2C%20pandas-blue)

<em>Built with the tools and technologies:</em>  
🐍 Python • 🌐 Requests • 🍲 BeautifulSoup • 📊 CSV/JSON  

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Overview

This project scrapes data from a provided webpage, extracting:

- Headings (h1, h2)
- Paragraphs and list items
- Product tables with details like product name, price, and stock status
- Structured product cards with multiple attributes
- Form fields with their attributes and defaults
- Links and embedded video URLs

The extracted data is saved into CSV and JSON files for easy consumption.

---

## Features

- Scrape headings, paragraphs, list items from HTML
- Extract tabular data (products, prices, stock) into CSV
- Extract complex product cards into JSON
- Extract form input/select/textarea field metadata to JSON
- Extract all links and iframe video URLs into JSON files
- Clean and structured export of scraped data

---

## Project Structure

└── Webscraping/
    ├── Books.json          # Extracted product card data in JSON
    ├── cards.json          # Product card details in JSON
    ├── fields.json         # Form fields metadata in JSON
    ├── links.json          # All anchor links and iframe video URLs in JSON
    ├── Practice.csv        # Extracted headings, paragraphs, list items in CSV
    ├── Prods.csv           # Extracted product table data in CSV
    └── Webscraping.ipynb   # Jupyter notebook with scraping code
## Getting Started

### Prerequisites

- Python 3.7+
- `requests` library
- `beautifulsoup4` library
- `pandas` library (optional, but recommended)

Install dependencies using pip:

pip install requests beautifulsoup4 pandas

### Installation

#### 1. Clone the repository:

git clone https://github.com/Abdelrahman-Shamikh/DEPI-Assignments.git

#### 2. Navigate to the scraping project folder:

cd DEPI-Assignments/Webscraping

#### 3. (Optional) Open the Jupyter Notebook:

jupyter notebook Webscraping.ipynb

### Usage

Run the Python script or Jupyter Notebook cells to:

- Fetch the webpage
- Parse and extract the desired elements
- Save the outputs as CSV and JSON files in the project directory

## Roadmap

- Basic scraping of headings, paragraphs, and lists
- Extract tabular product data
- Extract detailed product cards
- Extract form fields and default values
- Extract links and embedded video URLs
- Add error handling and retries for network requests
- Support scraping multiple pages or websites
- Integrate scraping scheduling and automation

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request describing your changes

## Acknowledgments

Thanks to BeautifulSoup and Requests libraries for making web scraping easier

Inspiration and guidance from DEPI program

Sample data and webpage used for practice

<div align="right">

[![][back-to-top]](#top)

</div>

[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-151515?style=flat-square
