# Mars Data Analysis Project

## Overview
This project involves web scraping and analysis of data related to Mars. It focuses on two key deliverables: extracting information from a Mars news website and analyzing weather data from the Mars rover, Curiosity.

## Deliverables

### Deliverable 1: Mars News Article Scraping

- **Objective**: Scrape titles and preview text from Mars news articles.
- **Method**: Implemented automated web scraping using Python libraries like BeautifulSoup and Splinter.
- **Results**: Extracted news articles are stored as a list of dictionaries, with each dictionary containing the `title` and `preview` text of an article.

### Deliverable 2: Mars Weather Data Analysis

- **Objective**: Scrape and analyze Mars weather data, focusing on temperature and atmospheric pressure.
- **Method**:
  - Utilized Python with Pandas and Matplotlib for data analysis and visualization.
  - Scraped weather data includes temperature and pressure readings from Curiosity's location on Mars.
- **Analysis**:
  1. **Average Low Temperature by Month**: Identified the average low temperature for each Martian month and visualized the data using a bar chart.
  2. **Average Atmospheric Pressure by Month**: Calculated the average pressure for each month and displayed it through a bar chart.
  3. **Martian Year in Earth Days**: Estimated the length of a Martian year in Earth days based on the data span.

## Files in the Repository

- `part_1_mars_news.ipynb`: Jupyter Notebook containing the code for the first deliverable.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for the second deliverable, focusing on weather data analysis.
- `mars_data.csv`: Exported CSV file containing the scraped Mars weather data.
- `README.md`: This file, providing an overview of the project and its contents.

## How to Run the Notebooks

1. **Prerequisites**:
   - Ensure Python is installed along with libraries: BeautifulSoup, Pandas, Matplotlib, and Splinter.
   - A web driver for Chrome or Firefox should be installed for Splinter.
2. **Running the Notebooks**:
   - Open the Jupyter Notebooks in an environment that supports IPython (like JupyterLab or VSCode).
   - Run each cell in the notebooks to execute the scraping and analysis.

## Conclusion

This project demonstrates the power of web scraping in gathering data from online sources and the use of Python's analytical libraries to derive meaningful insights from the collected data.

---


