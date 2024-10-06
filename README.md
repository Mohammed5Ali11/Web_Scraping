# Web Scraping Projects

This repository contains multiple web scraping projects, each focused on extracting different types of data from various sources. Below is a list of the projects and their corresponding files.

## Projects Overview

1. **FIFA Player Cards Scraper**
   - **Files**: `FIFA_Player.ipynb`, `FIFA_Player_Cards.csv`, `FIFA_Player_Cards.xls`, `FIFAPLAYERCSV.xlsx`
   - **Description**: This project scrapes player card data (name, position, ratings, and prices) from the FIFA Ultimate Team 25 players' webpage on Futwiz. The extracted data includes various player stats like PAC, SHO, PAS, DRI, DEF, and PHY.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`FIFA_Player_Cards.csv`, `FIFA_Player_Cards.xls`, `FIFAPLAYERCSV.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script iterates through multiple pages on the website, extracts the required player data, and saves it into the specified CSV file.

## How to Run

1. **Install Requirements**: Ensure Python is installed and then install the required libraries:

   ```bash
   pip install -r requirements.txt
