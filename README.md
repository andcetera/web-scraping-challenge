# Mars News and Weather Analysis
Scraping Mars news &amp; weather data using Splinter and Beautiful Soup for statistical analysis using Python Pandas and Matplotlib
- - -
![Curiosity_selfie](Images/curiosity.png)

Image Credit: NASA/JPL-Caltech/MSSS
- - -
## Project Structure  
### Code Files:  
All project code can be found in the [Deliverables](Deliverables/) folder.  
**Part 1 Mars News:** [mars_news.ipynb](Deliverables/mars_news.ipynb)  
**Part 2 Mars Weather:** [mars_weather.ipynb](Deliverables/mars_weather.ipynb)  

### Output:  
Scraped news articles & weather data can be found in the [Output](Output/) folder.  
**Mars News:** [mars_news_articles.json](Output/mars_news_articles.json)  
**Mars Weather:** [mars_weather_data.csv](Output/mars_weather_data.csv)  

### Images:  
Graphs generated from weather analysis can be found in the [Images](Images/) folder.  
**Average Temperature:** [ave_temp.png](Images/ave_temp.png)  
**Average Pressure:** [ave_pssr.png](Images/ave_pssr.png)  
**Daily Temperatures:** [daily_temps.png](Images/daily_temps.png)  

- - -
## Background
This new assignment consists of two technical products. You will submit the following deliverables:

- **Deliverable 1:** A Jupyter notebook containing code that scrapes the Mars news titles and preview text and prints/stores them in the following format:

```
{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
 ```
 
- **Deliverable 2:** A Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data.

Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    - Find the average minimum daily temperature for all of the months.
    - Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    - Find the average daily atmospheric pressure of all the months.
    - Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    - Visually estimate the result by plotting the daily minimum temperature.

- - - 

## Deliverable #2 Analysis Results:

Here’s an explanation of the column headings:

    - `id`: the identification number of a single transmission from the Curiosity rover
    - `terrestrial_date`: the date on Earth
    - `sol`: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    - `ls`: the solar longitude
    - `month`: the Martian month
    - `min_temp`: the minimum temperature, in Celsius, of a single Martian day (sol)
    - `pressure`: The atmospheric pressure at Curiosity's location


### References
The [Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from [NASA's Mars News](https://mars.nasa.gov/) website in November 2022. Images are used according to the [JPL Image Use Policy](https://www.jpl.nasa.gov/jpl-image-use-policy), courtesy NASA/JPL-Caltech.