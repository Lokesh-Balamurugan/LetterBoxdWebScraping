# LetterBoxdWebScraping

## Overview

This project is a comprehensive web scraping tool designed to extract detailed information about movies from Letterboxd, a popular social networking site for movie enthusiasts. The script navigates through the site, collecting data on various films released in the 2020s, including ratings, synopses, directors, genres, and more. Additionally, it integrates data from IMDb for a more comprehensive dataset.

## Features

- Extracts movie details such as taglines, synopses, director names, genres, and production studios.
- Retrieves ratings and user engagement data from both Letterboxd and IMDb.
- Utilizes Selenium for dynamic web page interaction.
- Stores extracted data in a structured format using Pandas DataFrames.
- Includes data visualization and analysis of the collected movie information.

## Technologies Used

- Python
- Libraries: bs4 (BeautifulSoup), pandas, seaborn, matplotlib, requests, re, selenium
- Selenium WebDriver for Chrome

## Installation

1. Clone the repository:

   ``` git clone [repository URL]```

3. Install the required Python libraries:
   
   ```pip install bs4 pandas seaborn matplotlib requests selenium```

5. Ensure you have the appropriate WebDriver for Chrome installed on your system.

## Output

The CSV file, `movies.csv`, contains the scraped movie data. 

## Data Analysis

The project includes a comprehensive analysis of the extracted movie data, highlighting trends and patterns in movie ratings, genres, production countries, and languages.

## Acknowledgements

Thanks to Letterboxd for providing a rich dataset and IMDb for additional movie details.
