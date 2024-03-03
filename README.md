# Module11_Web-Scraping-Challenge
Web Scraping - Week 11 - Data Analytics Boot Camp - University of Oregon


## Part 1: Scrape Titles and Preview Text from Mars News

### Instructions:
Utilize automated browsing to navigate through the [Mars news website](https://static.bc-edx.com/data/web/mars_news/index.html) using Spliter. With Beautiful Soup, scrape the article titles and preview text, and save the information as a JSON file.

![JSON Preview](images\json_preview.JPG)

---

## Part 2: Scrape and Analyze Mars Weather Data

### Instructions:

Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).  Extract the weather data from the table on the website and add it to a Pandas DataFrame with the appropiate data type for each column.  Then, answer the following questions:

- **Q:  How many months exist on Mars?**
- A:  There are 12 Martian months per Martian year.

- **Q:  How many Martian (and not Earth) days worth of data exist in the scraped dataset?**
- A:  There are 1867 Martian days of data in the dataset.

- **Q:  What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:**

  - **Find the average minimum daily temperature for all of the months.**
  - ![Average Minimum Daily Temp per Month](images\3-avg_min_temp.JPG)

  - **Plot the results as a bar chart.**
  - ![Mars Average Temperature Chart](images\Mars-Average-Temperature.png)

- **Q:  Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:**

  - **Find the average daily atmospheric pressure of all the months.**
  - ![Average Pressure per Month](images\4-avg-pressure.JPG)

  - **Plot the results as a bar chart.**
  - ![Mars Average Pressure per Month](images\Mars-Average-Pressure.png)

- **Q:  About how many terrestrial (Earth) days exist in a Martian year? To answer this question:**

  - **Consider how many days elapse on Earth in the time that Mars circles the Sun once.**

  - **Visually estimate the result by plotting the daily minimum temperature.**
  - ![Mars Temperature per Earth Day](images\Mars-Temp-Earth-Days.png)
  - A:  Visually, we can look at the chart and determine where the temperature midpoint lands.  In this case, the midpoint from day 0 matches the midpoint around 650.  A Google search confirms that one Martian year is equivalent to 687 earth days.

Once complete, export the website data to a CSV file.


