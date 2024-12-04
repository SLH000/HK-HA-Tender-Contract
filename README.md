# HK HA Tender Contract 

This project leverages Streamlit to build an interactive web app for analyzing and visualizing hospital tender data from Hong Kong's Hospital Authority (HK HA). It scrapes HTML tables, cleans the data, categorizes contractors, and provides filtering options for users. The data is presented with a table and a bar chart to show contractor distribution. Users can also download the filtered contractor list.

## Features

- **Data Scraping**: The app scrapes an HTML table from a user-provided URL.
- **Data Cleaning**: The app cleans and organizes the data, renaming columns, removing irrelevant rows, and categorizing tender subjects.
- **Filtering**: Users can filter contractors by hospital and category via the sidebar.
- **Data Download**: Users can download the filtered contractor list as a CSV file.
- **Data Visualization**: Displays a bar chart showing the distribution of contractors.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Streamlit
- Pandas
- Requests
- BeautifulSoup4
- NumPy
- Plotly

You can install the required libraries with:

```bash
pip install streamlit pandas requests beautifulsoup4 numpy plotly

```

## File Structure

- **app.py:** The main Streamlit app script that processes the data and displays it.
- **requirements.txt:** List of required libraries for the project.
- **data/:** Directory to store any data files or CSVs generated by the app (optional).
- **Tableau Workbook:** Dynmaic Dashboard for data visualization 
- **LICENSE:** The license file (optional).

## Usage

Clone the repository or download the app script.
Install the required dependencies by running:

```bash
pip install -r requirements.txt

```

Run the Streamlit app by executing the following command:

```bash
streamlit run app.py

```

### Key Sections in the README.md:

- **Features**: Highlights the main functionalities of the app.
- **Prerequisites**: Lists the required libraries and tools to run the app.
- **File Structure**: Explains the organization of the project files.
- **Usage**: Step-by-step guide on how to run the app, install dependencies, and use it.
- **Data Cleaning and Categorization**: Describes the data cleaning process and categorization logic.
- **Data Filtering**: Explains how users can filter the data.
- **Visualization**: Describes how the data is visualized in a bar chart.
- **Contributing**: Encourages contributions to the project.
- **License**: Information about the project license.
