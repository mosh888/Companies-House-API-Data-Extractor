Data Extractor for Companies House API

Overview

The RVA Data Miner for Companies House API is a Jupyter Notebook designed to extract and process company details from the Companies House API. 
The notebook filters out dissolved or retired entities and companies with only one director residing in the UK or England. 
The processed results are displayed in a structured format for further analysis.

Features:

Connects to the Companies House API.
Extracts detailed information about companies.
Filters out dissolved, retired entities, and companies with only one director residing in the UK or England.
Processes and displays the results in a structured format.

Requirements:

Python 3.x
Jupyter Notebook
requests library
pandas library
openpyxl library (for Excel file handling)
beautifulsoup4 library (for web scraping)
