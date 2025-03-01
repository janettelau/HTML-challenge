# HTML-challenge
**Objective**: Extract information using automated browsing with Splinter and HTML parsing with Beautiful Soup.

## Tools and Libraries
- Visual Studio Code
- Python
- Pandas
- Matplotlib
- splinter
- BeautifulSoup4

## Setup and Usage
1. Clone this repository to your local machine using `git clone`.
2. Navigate to the cloned directory in Visual Studio Code.
3. Open the Jupyter Notebook `part_1_mars_news.ipynb`.
4. Run each cell sequentially to extract the HTML code using automated browsing then scrape news titles and previews.
5. Open the Jupyter Notebook `part_2_mars_weather.ipynb`.
6. Run each cell sequentially to scrape and analyze Mars weather data.

## Project Breakdown
#### Part 1: Scrape Titles and Preview Text
* Automated browsing with Splinter was used to visit the Mars news website.
* Extracted the HTML code with Beautiful Soup.
* Scraped and extracted article titles and preview texts.
* Stored the scraped data in a list of dictionaries.

#### Part 2: Scrape and Analyze Mars Weather Data
* Scraped weather data in the HTML table using Beautiful Soup and stored it in a DataFrame called `mars_df`.
* Analyzed the data to answer the following questions, with visualizations for questions Q3-Q5:
    1. How many months exist on Mars?
    2. How many Martian days' worth of data are there?
    3. Which month, on average, has the lowest temperature?
    4. Which month, on average, has the lowest atmospheric pressure? The highest? The highest?
    5. How many terrestrial days exist in a Martian year?
* Exported the DataFrame to a CSV file.
