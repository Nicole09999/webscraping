# webscraping


---

# Top 50 Films Data Extraction

This script fetches data from a specific URL representing the top 100 most highly-ranked films and extracts the information about the top 50 films from it. It then filters films released from the year 2000 onwards and saves the data into a SQLite database and a CSV file.

## Prerequisites

- Python 3.x
- Required Python libraries: `requests`, `sqlite3`, `pandas`, `bs4 (Beautiful Soup)`

## Setup

1. Clone or download the repository to your local machine.
2. Ensure you have the required Python libraries installed. If not, you can install them using pip:

    ```bash
    pip install requests
    pip install pandas
    pip install beautifulsoup4
    ```

## Usage

1. Run the script `top_films_extraction.py`.
2. The script will fetch data from the specified URL, extract information about the top 50 films released from the year 2000 onwards, and save the data into a SQLite database named `Movies.db` and a CSV file named `top_50_films.csv`.
3. You can access the extracted data from the SQLite database or CSV file as per your convenience.

