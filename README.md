# Homework: Intro Scraping Practice

## Description

This Jupyter notebook is designed as an introductory exercise in web scraping using Python. The primary focus is on practicing scraping skills by examining the "Published Reproductions" section of Soma's Investigate.ai project.

## Structure

The notebook is organized into the following sections:

### 0) Setup

- Import necessary libraries: `requests`, `BeautifulSoup`, and `pandas`.

### 1) Grab the HTML for [Investigate.ai](https://investigate.ai/)

- Use the `requests` library to fetch the HTML content of the target website.

### 2) Use `BeautifulSoup` to convert the HTML into its DOM representation

- Parse the fetched HTML content using `BeautifulSoup`.

### 3) Use `.select(...)` to select the "Published reproductions" section

- Utilize CSS selectors to extract the specific section of interest from the parsed HTML.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `pandas` library
 
