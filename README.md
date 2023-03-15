# Module-11-Challenge

**Background**
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

What You're Creating
This new assignment consists of two technical products. You will submit the following deliverables:

**Deliverable 1:** Scrape titles and preview text from Mars news articles.

**Deliverable 2:** Scrape and analyze Mars weather data, which exists in a table.

**Instructions**
**Part 1:** Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

**Part 2:** Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

**Mars Weather Analysis**
Scrape of Mars Temperature data used to analyze the weather information.

![mars_website_data](https://user-images.githubusercontent.com/117309455/225374306-3e3b21f8-9355-4699-883c-516676c34404.png)

Dataframe created for ease of analysis

![mars_weather_df](https://user-images.githubusercontent.com/117309455/225378587-52673630-7109-4e89-8310-a7e6817b0860.png)


**Summary of Analysis**

Mars and Earth have 12 months. There were a total of 1977 Martian days of data collected for the Mars weather.

Temperatures on Mars are the lowest in the third month with an average minimum tempterature of -83.3 and the highest temperatures are experienced in the eighth month with an average high of -68.4.

![mars_Avg_min_temp](https://user-images.githubusercontent.com/117309455/225376389-efabafed-ecc5-4815-ab21-03ea3dbcf468.png)

The daily minimum temperatures can be used to estimate the length of a Martian year (approx. 675 days on Earth) by calculating the distance peak-to-peak. 

![mars_min_temp](https://user-images.githubusercontent.com/117309455/225377719-f857422a-8938-4c7e-bd3c-62757686ac63.png)

The sixth month shows the lowest atomsphereic pressure, with the nineth month being the highest which follows the highest temps in the eighth month.

![mars_avg_pressure](https://user-images.githubusercontent.com/117309455/225376749-e2cc3653-06a1-489f-8c29-949b4305552a.png)

