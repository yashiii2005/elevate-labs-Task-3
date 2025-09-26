# News Headlines Scraper

This Python project scrapes the top news headlines from a news website (default: BBC News) using requests and BeautifulSoup. It cleans the data to remove any empty or NaN values, and saves the headlines in a single-column text file with a custom header.

## Features
- Fetches HTML content from the news website
- Parses `<h2>` tags to extract headlines
- Cleans and filters out invalid entries (NaN, empty)
- Outputs cleaned headlines in a single-column file with a custom header

## Requirements
- Python 3.x
- `requests`
- `beautifulsoup4`
- `pandas`
