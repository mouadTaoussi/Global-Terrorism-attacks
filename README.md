## Global terrorism attacks analysis

This dataset covers terrorist attacks that occured in the past in different countries of the globe, all these devastating events in the dataset are going to be analysed using the Pandas library in Python, as well as the output is going to be served to build the final report using the power BI tool, tool for business intelligence.

the original dataset is not included in this repository, due to large volume that exeeds the minimum volume allowed in github, the original dataset can be found at this [kaggle dataset](https://www.kaggle.com/datasets/START-UMD/gtd)

## Data elements

**eventid**: A 12-digit Event ID system. First 8 numbers – date recorded “yyyymmdd”. Last 4 numbers – sequential case number for the given day (0001, 0002 etc).</br>
**iyear**: This field contains the year in which the incident occurred.</br>
**imonth**: This field contains the number of the month in which the incident occurred.</br>
**iday**: This field contains the numeric day of the month on which the incident occurred.</br>
**extended**:</br>
    - 1 = "Yes" The duration of an incident extended more than 24 hours.</br>
    - 0 = "No" The duration of an incident extended less than 24 hours.</br>
**country**: This field identifies the country code.</br>
**country_txt**: This field identifies the country or location where the incident occurred.</br>
**region**: This field identifies the region code based on 12 regions.</br>
**alternative_txt**</br>
**attacktype1_txt**</br>
**attacktype2_txt**</br>
**targtype1_txt**</br>
**targsubtype1_txt**</br>

## Key questions

here are some key questions we can explore and include in our data visualization report:

1. What is the trend in the number of terrorist incidents over the years (iyear)?
2. Are there any specific months (imonth) that have a higher incidence of terrorist attacks?
3. Is there a difference in the duration of terrorist incidents (extended) between countries?
4. Which countries have the highest and lowest number of terrorist incidents (country_txt)?
5. How do the regions (region) compare in terms of the frequency of terrorist attacks?
6. Are there any trends in the extended duration of incidents over the years?
7. Can we identify patterns or trends in the occurrence of terrorist incidents based on the day of the month (iday)?
8. Are there any correlations between the country's location (country_txt) and the region (region) where terrorist incidents occur?

These questions should help us get started with analyzing the global terrorism dataset. We can use various data visualization techniques, such as time series plots, bar charts, and maps, to explore and present the data effectively in our report.