# Web Scraping Projects

This repository contains multiple web scraping projects, each focused on extracting different types of data from various sources. Below is a list of the projects and their corresponding files.

## Projects Overview

1. **FIFA Player Cards Scraper**
   - **Files**: `FIFA_Player.ipynb`, `FIFA_Player_Cards.csv`, `FIFA_Player_Cards.xls`, `FIFAPLAYERCSV.xlsx`
   - **Description**: This project scrapes player card data (name, position, ratings, and prices) from the FIFA Ultimate Team 25 players' webpage on Futwiz. The extracted data includes various player stats like PAC, SHO, PAS, DRI, DEF, and PHY.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`FIFA_Player_Cards.csv`, `FIFA_Player_Cards.xls`, `FIFAPLAYERCSV.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script iterates through multiple pages on the website, extracts the required player data, and saves it into the specified CSV file.

2. **Wuzzuf AI Job Listings Scraper**
   - **Files**: `wazzuf_AI_DATA.ipynb`, `WuzzafData.csv`, `WuzzafAIData.xls`, `WuzzufAiCSVData.xlsx`
   - **Description**: This project scrapes AI-related job listings (job title, company name, job type, location) from the Wuzzuf job search website. The extracted data includes job titles, company names, job types, and locations from several job postings.
   - **Data Format**: The data is saved in both CSV and Excel formats (`WuzzafData.csv`, `WuzzafAIData.xls`, `WuzzufAiCSVData.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script navigates through different pages of job search results on the Wuzzuf website and extracts relevant data into a CSV file.
3. **FielGoal Matches Scraper**
   - **Files**: `FIELGOL.ipynb`, `FIELGOAL.csv`, `FIELGOAL.xls`, `FIELGOALCSV.xlsx`
   - **Description**: This project scrapes match data (league name, team names, match results, stadium name, and match date) from the FielGoal matches webpage for the date 2024-09-28. The extracted data includes various matches from different leagues, including the Premier League, La Liga, Serie A, Bundesliga, and Saudi Pro League.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`FIELGOAL.csv`, `FIELGOAL.xls`, `FIELGOALCSV.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script sends a request to the specified URL, parses the HTML content, and extracts relevant match information, saving it into the specified CSV and Excel files.
4. **Mangalik Manga Scraper**
   - **Files**: `Mangalik.ipynb`, `Mangalik.csv`, `Mangalik.xls`, `MangaLIkCSV.xlsx`
   - **Description**: This project scrapes manga data (manga name, last chapter, and manga rating) from the Lekmanga website. It collects information from multiple pages to ensure a comprehensive list of available manga and their latest chapters.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`Mangalik.csv`, `Mangalik.xls`, `MangaLIkCSV.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script iterates through the first 100 pages of the Lekmanga website, extracts relevant manga information, and saves it into the specified CSV and Excel files.
5. **Anaconda Packages Scraper**
   - **Files**: `Anaconda.ipynb`, `Anacondaa.csv`, `Anacondaa.xls`, `Book1.xlsx`
   - **Description**: This project scrapes package data (package name, access, summary, last updated date, and install command) from the Anaconda repository. It collects data across multiple pages to compile a comprehensive list of available packages.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`Anacondaa.csv`, `Anacondaa.xls`, `Book1.xlsx`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script iterates through 73 pages of the Anaconda repository, extracts relevant package information, fetches the install command for each package, and saves it into the specified CSV and Excel files.
6. **Countries Data Scraper**
   - **Files**: `Countries.ipynb`, `Countries.csv`, `CountriesCSV.xlsx`, `Countries (1).xls`
   - **Description**: This project scrapes country data (country name, capital, population, and area in square kilometers) from the "Scrape This Site" website. It compiles a list of countries with their respective details for easy reference.
   - **Data Format**: The scraped data is saved in both CSV and Excel formats (`Countries.csv`, `CountriesCSV.xlsx`, `Countries (1).xls`).
   - **Libraries Used**: Requests, BeautifulSoup, CSV
   - **How It Works**: The script extracts the details for each country block from the webpage, including country name, capital, population, and area in square kilometers. This information is then written into CSV and Excel files for further use or analysis.
7. **Books Scraper**
   - **Files:** `Books.ipynb`, `Books.csv`, `Books.xls`, `BooksCSV.xlsx`  
   - **Description:** This project scrapes book data (book name, rating, and price) from the website 'Books to Scrape'. It compiles a list of available books along with their ratings and prices.  
   - **Data Format:** The scraped data is saved in both CSV and Excel formats (`Books.csv`, `Books.xls`, `BooksCSV.xlsx`).  
   - **Libraries Used:** `requests`, `BeautifulSoup`, `csv`  
   - **How It Works:** The script iterates through 51 pages of the website, extracts the book name, rating, and price, and writes the data into the specified CSV and Excel files.




## How to Run

1. **Install Requirements**: Ensure Python is installed and then install the required libraries:

   ```bash
   pip install -r requirements.txt
