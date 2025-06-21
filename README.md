# Python Job Board Scraper

A Python script that scrapes job listings from the official python.org/jobs board, processes the data, and saves it to a clean CSV file. This project demonstrates skills in web scraping, data manipulation, and professional code organization.

## 🚀 Features

-   Fetches data from a live website (`python.org/jobs`).
-   Parses HTML using BeautifulSoup to extract specific job details.
-   Handles missing or inconsistent data points gracefully.
-   Organizes the extracted data into a structured table using the pandas library.
-   Saves the final, clean data to a `python_jobs.csv` file.

## 🛠️ Technologies Used

-   **Python 3**
-   **Requests:** For making HTTP requests to the website.
-   **BeautifulSoup4:** For parsing HTML content.
-   **Pandas:** For data manipulation and saving to CSV.

## ⚙️ How to Use

1.  Clone the repository to your local machine.
2.  Install the necessary libraries:
    ```sh
    pip install requests beautifulsoup4 pandas
    ```
3.  Run the script from your terminal:
    ```sh
    python your_script_name.py
    ```
4.  A file named `python_jobs.csv` will be created in the same directory.

## 📊 Sample Output

Here is a sample of the final data table produced by the script:
![Screenshot_20250621_224618](https://github.com/user-attachments/assets/ae74a0dd-43a1-43db-8526-95b069d8f633)
