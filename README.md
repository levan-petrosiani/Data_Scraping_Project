# Web Scraping Project: Largest Companies in the U.S.

## Project Overview
This project demonstrates the process of web scraping using Python to extract data from a Wikipedia page about the largest companies in the United States by revenue. The extracted data is cleaned and saved into a structured format for further analysis.

## Features
- Scrapes data from a publicly available website using the `BeautifulSoup` library.
- Extracts and processes an HTML table into a Pandas DataFrame.
- Saves the cleaned data into a CSV file.

## Dataset
The scraped dataset includes the following columns:
- **Rank**: The rank of the company based on revenue.
- **Name**: The company's name.
- **Industry**: The sector the company operates in.
- **Revenue (USD millions)**: The company's annual revenue in millions of USD.
- **Revenue growth**: Percentage growth in revenue compared to the previous year.
- **Employees**: Total number of employees in the company.
- **Headquarters**: The city and state of the company's headquarters.

## Technologies Used
- **Python**: Programming language used for web scraping and data processing.
- **BeautifulSoup**: Library for parsing HTML and extracting information.
- **Pandas**: Library for data manipulation and analysis.
- **Requests**: Library to send HTTP requests and retrieve webpage content.

## Files Included
- **`Data_Scraping_Project.ipynb`**: The Jupyter Notebook containing the web scraping code.
- **`Companies.csv`**: The resulting dataset saved after processing.

## Steps to Reproduce
1. Clone the repository to your local machine.
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory and open the Jupyter Notebook.
   ```bash
   cd <project_directory>
   jupyter notebook Data_Scraping_Project.ipynb
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook cells to scrape the data and save the results.


## Acknowledgments
Data sourced from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue).

