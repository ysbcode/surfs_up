# Surfs_up

Analyzing weather data using Python, Jupyter Notebook, SQLite, Flask applications.

# Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one for June and the other for December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method.

## Analysis Results

The image below shows the descriptive statistics of temperature for the month of June for several years.

![](https://github.com/ysbcode/surfs_up/blob/main/images/June_temp_summary.png?raw=true)

We have also added an image for the descriptive statistics of temperature for the month of December for several years. 

![](https://github.com/ysbcode/surfs_up/blob/main/images/December_temp_summary.png?raw=true)

### Points to consider:
 - The Average temperatures for both months are very close: 74 for June and 71 for December. 
 - The maximum temperatures for both months are very close: 85 for June and 83 for December.
 - Standard deviation is 3.25 in June and 3.75 in December, making December a slightly more volatile.
 
 ## Overall Summary
 
 As our analysis shows, the average and max temperatures for June and December are very close. This shows that both months are suitable for running the surf shop. Additional reasearch items include: 
 - We can refactor the code to compare temperatures in the fall and spring to get an overall picture of temperature volatility for the full year. This can then be used to make a judgement on whether th shop should be a year-round or seasonal thing. 
 - We can also compare the descriptive statistics for precipitation with temperature for the the two months.
