# Web Scraper

## Overview
This Web Scraper is a Streamlit-based application that allows users to scrape website content, clean the extracted data, and parse specific information using the Ollama language model. The application leverages Selenium for web scraping and BeautifulSoup for DOM parsing, providing an interactive interface to input URLs, view scraped content, and extract targeted information based on user-defined descriptions.

## Features
- **Web Scraping**: Fetches HTML content from a specified URL using Selenium WebDriver.
- **Content Cleaning**: Extracts and cleans the body content of the webpage, removing scripts, styles, and unnecessary whitespace.
- **Content Parsing**: Splits the cleaned content into chunks and processes it with the Ollama LLM to extract information based on user-provided descriptions.
- **Interactive UI**: Built with Streamlit, allowing users to input URLs, view DOM content, and define parsing instructions through a web interface.
