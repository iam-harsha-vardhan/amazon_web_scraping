# Web Scraping from Amazon with Python

## Overview
This project demonstrates how to scrape data from Amazon's Best Sellers page in the Teaching & Education category using Python. The goal is to collect information about the top 50 authors and their ratings.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Output](#output)
- [License](#license)

## Technologies Used
- Python
- Requests library
- BeautifulSoup library
- Pandas library

## Installation
To run this project, you need to have Python installed on your machine. You can install the required libraries using pip. If you are using Jupyter Notebook or Google Colab, you can run the following command:

```bash
pip install beautifulsoup4 requests pandas
```

## Usage
Clone this repository to your local machine:

```bash
git clone https://github.com/iam-harsha-vardhan/amazon_web_scraping.git
```

Navigate to the project directory:

```bash
cd amazon_web_scraping
```

Open the Jupyter Notebook file and run the cells to scrape data from Amazon.

## Code Explanation
The code is structured into several steps:

1. **Importing Libraries**: Necessary libraries are imported for web scraping and data manipulation.
2. **Setting Up the Target URL and Headers**: The base URL for the Amazon Best Sellers page is defined, along with HTTP headers to mimic a browser.
3. **Collecting Data from Multiple Pages**: A loop iterates through multiple pages, sending requests and extracting author names and ratings.
4. **Storing and Saving the Data**: The collected data is stored in a Pandas DataFrame and saved to a CSV file.

## Output
The output of the scraping process is a CSV file named `amazon_top_50_books_authors_ratings.csv`, which contains the authors and their ratings. You can view a sample of the data in the DataFrame.



