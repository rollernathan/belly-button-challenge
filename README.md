# belly-button-challenge
Module 14 Challenge

This project contained three parts. The first part was to create a bar chart to display the top 10 operational taxonomic units (OTUs) found in a specific individual test subject's navel (belly button). The second part was to create a bubble chart showing the number of bacteria for each OTU found in a specific individual test subject's navel. The third part was to display the metadata information for the selected individual test subject being shown in the charts.


## Part 1: Bar Chart

For the Test Subject ID selected from the dropdown menu, I created a bar chart with the following characteristics:
- OTU ID as the labels
- Values of that OTU ID present in the sample as the values
- Labels of the OTUs as the text shown when hovering over the specific bar in the bar chart

An example of the bar chart is shown below for Test Subject 956.

![bar_chart_956.png]()


## Part 2: Mars Weather Data

I was asked to scrape weather data from a Mars temperature data site. Using the [Mission To Mars site](https://static.bc-edx.com/data/web/mars_facts/temperature.html), I pulled a list of 1867 Martian Days data points and created a data frame of the information to analyze. The first five rows of data have been included in the image below.

![temperature_df](https://github.com/rollernathan/Mars_webscraping_C11/blob/main/images/temperature_df.png)

As part of the analysis, I was asked to answer five questions. The answers to those questions are included below.


### How many months exist on Mars?

Similar to Earth, there are <b> twelve (12) months on Mars</b>. The image below shows the number of rows in the data frame for each month.

![months.png](https://github.com/rollernathan/Mars_webscraping_C11/blob/main/images/months.png)

### How many Martian (and not Earth) days worth of data exist in the scraped dataset?

There are 1,867 unique Martian days worth of data in the scraped dataset.

### What are the coldest and the warmest months on Mars (at the location of Curiosity)?

The <b> warmest month on Mars (at the Curiosity location) is Month 8</b> with an average minimum temperature of -68.382979 <sup>o</sup>C. Conversely, the <b> coldest month on Mars (at the Curiosity location) is Month 3</b> with an average minimum temperature of -83.307292 <sup>o</sup>C. The bar graph below shows the average minimum temperature by month from coldest to warmest.

![temp_months.png](https://github.com/rollernathan/Mars_webscraping_C11/blob/main/images/temp_months.png)

### Which months have the lowest and the highest atmospheric pressure on Mars?

The month with the <b> lowest atmospheric pressure on Mars (at the Curiosity location) is Month 6</b> with an average atmospheric pressure of 745.054422. Conversely, the month with the <b> highest atmospheric pressure on Mars (at the Curiosity location) is Month 9</b> with an average atmospheric pressure of 913.305970. The bar graph below shows the average atmospheric pressure by month from lowest to highest.

![pressure_months.png](https://github.com/rollernathan/Mars_webscraping_C11/blob/main/images/pressure_months.png)

### About how many terrestrial (Earth) days exist in a Martian year?

There are approximately <b> 675 terrestrial (Earth) days in a Martian year</b>. To identify the number of Earth days, I graphed the minimum temperature from each day on a line graph, shown below, and looked at the approximate difference from one maximum to the next or one minimum to the next. To get 675, I calculated 1750 - 1075 because those are two easily identifiable minimums in the graph.

![year_on_mars.png](https://github.com/rollernathan/Mars_webscraping_C11/blob/main/images/year_on_mars.png)


### Sources
Data for the Mars News analysis scraped from [Mars Planet Science](https://static.bc-edx.com/data/web/mars_news/index.html) as of August 12, 2024.

Data for Mars Weather Data analysis scraped from [Mission To Mars](https://static.bc-edx.com/data/web/mars_facts/temperature.html) as of August 12, 2024.
