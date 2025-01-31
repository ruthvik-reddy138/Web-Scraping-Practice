# Virat Kohli International Centuries Scraper

## Project Description
This project extracts data from Wikipedia on Virat Kohli's international centuries using Python. It utilizes `BeautifulSoup` for web scraping and `pandas` for data handling. The script retrieves the data, structures it into a DataFrame, and provides it in a structured format for further analysis.

## Technologies Used
- **Python**
- **BeautifulSoup**: For parsing HTML and extracting data from the Wikipedia page.
- **Requests**: To fetch webpage content.
- **Pandas**: For structuring and processing the extracted data.

## Installation
Ensure you have Python installed. Install required dependencies using:
```sh
pip install beautifulsoup4 requests pandas
```

## How to Run
1. Clone this repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the script:
   ```sh
   python script.py
   ```

## Script Breakdown
1. **Fetch Webpage**: Uses `requests.get()` to retrieve Wikipedia content.
2. **Parse HTML**: Extracts tables using `BeautifulSoup`.
3. **Extract Data**: Retrieves column headers and row data.
4. **Store in DataFrame**: Uses `pandas` to format and clean extracted data.
5. **Type Conversion**: Converts specific columns into appropriate data types.

## Expected Output
- A structured `pandas.DataFrame` containing details of Virat Kohli’s international centuries.
- The DataFrame includes information such as:
  - Runs scored
  - Opponent team
  - Venue
  - Match date
  - Format (Test, ODI, T20I)

## Future Enhancements
- Store data in a CSV file for persistent storage.
- Automate updates by scheduling periodic scraping.
- Perform data analysis on Kohli’s centuries to identify trends.

## License
This project is open-source and available under the [MIT License](LICENSE).

