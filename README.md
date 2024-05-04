# Real-Estate
# Airbnb market analysis and real estate sales
# 1. Introduction
## Project Overview
The Airbnb Analysis project focuses on analyzing Airbnb data from the travel industry and property management domain. By leveraging various data analysis and visualization tools, we aim to extract valuable insights into pricing dynamics, availability patterns, and location-based trends in Airbnb listings.
# Objectives
The primary objectives of this project include:

1) Ensure data quality and consistency by addressing missing values, outliers, and duplicates.
2) Standardize data formats and rectify inconsistencies in column names or values.
3) Validate and clean geographic coordinates, zip codes, and other location-based data to maintain data integrity.
4) Utilize EDA techniques to grasp data distributions, trends, and interrelationships.
5) Summarize and visualize key features using descriptive statistics, histograms, scatter plot and heat map
6) Identify correlations between variables and uncover potential patterns or anomalies.
7) Analyzing geographic trends analysis to identify spatial clusters, hotspots, or patterns in Airbnb listings or amenities distribution.
8) Visualization process utilizes various tools and libraries, such as matplotlib, Seaborn, Plotly, to generate static and interactive visualizations like plots and charts.

# About Dataset

This dataset, titled 'Airbnb Market Analysis and Real Estate Sales Data (2019),' comprises a comprehensive collection of information pertaining to the Airbnb rental market and property sales in two distinct areas within California: Big Bear and Joshua Tree, along with their associated zip codes (92314, 92315, 92284, and 92252). The dataset provides monthly aggregated data, allowing for an in-depth analysis of rental and real estate market trends in these regions. It includes the following files:

## Datasets:
### Market Analysis:
This file contains listing-level information from 2019, aggregated on a monthly basis. It encompasses various metrics, such as unique property codes (unified_id), generated revenue, availability (openness), occupancy ratios, nightly rates, lead times, and average length of stay for reservations made each month. Additionally, it provides insights into property amenities.

### Amenities:
This file indicates whether a listing has specific amenities, denoting their presence with a value of 1 or their absence with a value of 0. Notably, it identifies the availability of a pool or hot tub in each listing.

### Geolocation:
This file contains latitude and longitude coordinates for each listing, enabling precise spatial analysis and visualization.

### Sales Properties:
This dataset provides information concerning properties available for sale within the study areas. In the Joshua Tree region (zip codes 92284 and 92252), there are two separate files—one presenting the overall information about sales properties and the other focusing on properties with pools.

This dataset is a valuable resource for researchers and analysts interested in gaining insights into the real estate and Airbnb rental markets in California, particularly within the specified regions.


# 2. Methodology
### Data Collection 
Gather relevant datasets from sources such as Airbnb listings, geolocation data, and market analysis reports.

### Data Cleaning
Identify and address missing values, outliers, and inconsistencies in the datasets to ensure data integrity and accuracy.

### Exploratory Data Analysis (EDA) 
Explore the datasets to understand distributions, trends, and relationships between variables using descriptive statistics and data visualization techniques.

### Geographic Analysis
Analyze geographic trends such as property density, proximity to attractions, and location-based insights to gain a deeper understanding of the market.


![download-10](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/d2bcc65f-5eb5-4b5d-95d4-2831f3ae4e34)



The visualization "Distribution of Data Points by Month" illustrates the spread of data across different months in the geolocation dataset. Each bar represents the count of data points corresponding to a specific month. The height of the bars indicates the frequency of data points recorded in each month. By observing the distribution, we can identify any noticeable seasonal trends or patterns in the data. we may observe higher counts during certain months, indicating periods of increased activity or data collection.
### Visualization
Create informative and visually appealing plots, charts, maps to communicate insights effectively to stakeholders.


![download](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/d660a231-306b-4eb4-8855-a946c72470b8)




The scatter plot "Geographical Distribution of Data Points" displays the spatial distribution of data points based on latitude and longitude coordinates. It provides insights into the geographic coverage of the dataset, highlighting concentrations or clusters of data points in specific regions. 




![download-1](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/db239545-84cf-4a78-a8cb-86f661abdcc0)


The bar plot "Top 5 Most Common Street Names (Excluding Unspecified)" illustrates the frequency of occurrence of the top 5 street names in the dataset, excluding instances where the street name is not specified. It provides insights into the most prevalent street names within the dataset, helping to identify common naming patterns or frequently encountered locations. This visualization aids in understanding the distribution of properties across different street names and their relative popularity.




![download-14](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/9becb398-f846-4c18-8dea-7cc8129213d5)


The bar plot "Top 5 Least Common Street Names (Excluding Unspecified)" displays the frequency of occurrence of the least common street names in the dataset, excluding instances where the street name is not specified. It highlights street names with the lowest frequency within the dataset, offering insights into less commonly encountered locations or unique naming conventions. This visualization aids in identifying outliers or rare occurrences among street names, which may have implications for property distribution or geographic analysis.




![download-15](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/795d2d2c-02c6-493e-864a-f63da91ffd4a)


The visualization above illustrates the distribution of hot tubs and pools among the properties in the dataset.

In the first subplot, "Distribution of Hot Tubs," the bar plot shows the count of properties with and without hot tubs. The blue bars represent the presence or absence of hot tubs, with "Absent" indicating properties without hot tubs and "Present" indicating properties with hot tubs. From this plot, it's evident that there are more properties without hot tubs compared to those with hot tubs.

In the second subplot, "Distribution of Pools," the bar plot displays the count of properties with and without pools. Similarly, the green bars represent the presence or absence of pools, with "Absent" indicating properties without pools and "Present" indicating properties with pools. Here, it's noticeable that the majority of properties do not have pools, as indicated by the higher count of "Absent" compared to "Present."

which could be useful for potential renters or buyers interested in such amenities.


![download-4](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/38225fbe-c0cb-4c88-a0cd-066bf32d4281)

The visualization above depicts the Average Revenue per month based on the market analysis 2019 data.

Each month is represented on the x-axis, while the revenue in dollars is shown on the y-axis. Notably, December stands out with the highest revenue, indicating a peak in earnings for the year. Conversely, April marks the lowest revenue, suggesting a dip in profitability during that period. However, the overall trend showcases a consistent increase in revenue over the course of the year, reflecting positive growth and financial performance.

- The graph illustrates the average revenue per month for a company in 2019.
- December recorded the highest revenue, indicating a peak in earnings.
- In contrast, April marked the lowest revenue, signaling a dip in profitability.
- Despite fluctuations, the overall trend shows a consistent increase in revenue throughout the year.
- Each month is represented on the x-axis, while revenue in dollars is displayed on the y-axis.

![download-5](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/1bd73eb0-c350-466e-ba81-21a98e9a94f1)

The visualization above depicts the Average Occupancy per month based on the market analysis 2019 data.
Each month is represented on the x-axis, while the average occupancy, measured in some unit (e.g., percentage or number of occupants), is depicted on the y-axis. Notably, December and February emerge as the months with the highest average occupancy, indicating peak demand or utilization during these periods. In contrast, May and April record the lowest average occupancy levels, suggesting reduced activity or usage during these months. Despite fluctuations, the overall trend underscores varying levels of occupancy throughout the year.

- The graph depicts the average occupancy per month in 2019.
- December and February register the highest average occupancy levels.
- Conversely, May and April record the lowest average occupancy.
- Each month is represented on the x-axis, while average occupancy is shown on the y-axis.
- The visualization offers insights into monthly occupancy patterns.
- It highlights periods of peak demand or utilization.
- Fluctuations in occupancy levels are observed throughout the year.
  
![download-6](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/f773b1ae-cfb1-4995-8441-841154eb2fb3)

The visualization above depicts the monthly trends of revenue and occupancy rates based on the market analysis 2019 data.

##### Monthly Trend of Revenue:
- The line plot shows the average revenue generated each month over the analyzed period.
- The x-axis represents the months, while the y-axis represents the average revenue.
- The yellow line illustrates the fluctuation in revenue over time.
###### Interpretation: 
Observing the trend helps in identifying seasonal patterns or trends in revenue generation. spikes or dips in revenue can indicate peak or off-peak seasons, respectively. Additionally, steady growth or decline in revenue over time can provide insights into the overall performance of the market.

##### Monthly Trend of Occupancy:
- The line plot shows the average occupancy rate each month.
- The x-axis represents the months, while the y-axis represents the average occupancy rate.
- The green line represents the trend in occupancy rates across different months.
###### Interpretation: 
Analyzing the occupancy trend helps in understanding demand patterns throughout the year. High occupancy rates suggest strong demand, while low occupancy rates may indicate periods of lower demand. Identifying peaks and troughs in occupancy can inform property management decisions, pricing strategies, and marketing efforts.

![download-16](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/ed2341b8-feb7-405c-846e-a078bd3d8890)


The visualization above depicts the quarterly trends of hot tub and pool presence among properties over different years.

In the left subplot, "Quarterly Trend of Hot Tub Presence," the bar plot shows the total count of hot tubs across different quarters. Each bar represents a quarter, and the height of the bars indicates the total number of hot tubs present in properties during that quarter. The bars are color-coded by year, allowing for a comparison of hot tub trends across different years.
Similarly, the right subplot, illustrates the total count of pools across quarters, with bars representing each quarter and color distinguishing between different years.
which could inform decisions related to property management, rental pricing, or marketing strategies.



![download-22](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/087a24ab-d23e-4911-9da8-56626bd74662)

The visualization above presents the  revenue and occupancy rates across different cities based on the market analysis 2019 data.

#####  Revenue by City:
- The left subplot illustrates the average revenue generated in each city.
- Cities are represented on the x-axis, while the average revenue is depicted on the y-axis.
- Each bar represents the average revenue for a specific city, with the height indicating the revenue value.
###### Interpretation:
This plot allows for a comparison of revenue generation across different cities. Cities with taller bars have higher average revenue, indicating stronger financial performance. Understanding revenue disparities among cities can guide investment decisions, marketing strategies, and resource allocation.

![download-23](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/a53f7e46-5758-426f-ae30-a077370d7e44)


#####  Occupancy by City:
- The right subplot displays the average occupancy rates for each city.
- Cities are shown on the x-axis, while the average occupancy rate is displayed on the y-axis.
- Each bar represents the average occupancy rate for a specific city, with the height indicating the occupancy percentage.
###### Interpretation: 
This plot facilitates the comparison of occupancy rates across different cities. Higher bars indicate cities with higher average occupancy rates, suggesting strong demand for accommodations. Identifying cities with consistently high occupancy rates can help in prioritizing investment opportunities and optimizing pricing strategies to maximize revenue.

![download-25](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/8d52c0f5-005b-4c4b-9766-ac31c50ac594)

The visualization above presents the  revenue and occupancy rates  based on the market analysis 2019 data.

##### Revenue by Zipcode :
- The left subplot illustrates the average revenue generated in the top 10 zip codes.
- Zipcodes are represented on the x-axis, while the average revenue is depicted on the y-axis.
- Each bar represents the average revenue for a specific zipcode, with the height indicating the revenue value.
###### Interpretation: 
This plot allows for a comparison of revenue generation among the top-performing zip codes. Zip codes with taller bars have higher average revenue, indicating stronger financial performance. Understanding revenue disparities among zip codes can inform investment decisions, marketing strategies, and resource allocation.

![download-24](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/18df3501-068b-4d93-99e8-4c44bd77c58f)


##### Occupancy by Zipcode :
- The right subplot displays the average occupancy rates for the top 10 zip codes.
- Zipcodes are shown on the x-axis, while the average occupancy rate is displayed on the y-axis.
- Each bar represents the average occupancy rate for a specific zipcode, with the height indicating the occupancy percentag
###### Interpretation: 
This plot facilitates the comparison of occupancy rates among the top-performing zip codes. Higher bars indicate zip codes with higher average occupancy rates, suggesting strong demand for accommodations. Identifying zip codes with consistently high occupancy rates can help prioritize investment opportunities and optimize pricing strategies to maximize revenue.




![download-7](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/f69483d3-1aea-42ec-8a5d-69b150e92c8e)
![download-8](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/e0da5167-bfc9-4ec9-96a3-edea6bc23f1a)
![download-9](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/9433c1bc-5797-4110-8add-b912e263bec7)

The scatter plots above depict relationships between different variables based on the market analysis 2019 data:

##### Scatter Plot of Revenue vs. Occupancy:
- This plot illustrates the relationship between revenue and occupancy rate.
- Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the occupancy rate, while the y-axis represents revenue.
###### Interpretation:
The scatter plot allows us to observe how changes in occupancy rates correspond to changes in revenue. Clusters of points with higher revenue may indicate properties with consistently high occupancy rates, suggesting a positive correlation between occupancy and revenue.

##### Scatter Plot of Revenue vs. Nightly Rate:
- This plot showcases the relationship between revenue and nightly rate.
- Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the nightly rate, while the y-axis represents revenue.
###### Interpretation:
The scatter plot helps identify how changes in nightly rates affect revenue generation. Clusters of points with higher revenue at lower nightly rates may indicate properties that attract more bookings due to competitive pricing or higher perceived value.

##### Scatter Plot of Nightly rate vs. Length of Stay:
- This plot visualizes the relationship between Nightly rate and length of stay.
-Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the nightly rate, while the y-axis represents the length of stay.
###### Interpretation: 
The scatter plot allows us to examine how the length of stay influences occupancy rates. Properties with longer average stays may exhibit higher occupancy rates, indicating potential opportunities to target guests seeking extended accommodations.

![download-17](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/1133d911-cc74-4773-b95b-9b0ce4710d7c)


The visualization above depicts the monthly trends of revenue and occupancy rates based on the market analysis data.

##### Monthly Trend of Revenue:
- The line plot shows the average revenue generated each month over the analyzed period.
- The x-axis represents the months, while the y-axis represents the average revenue.
- The yellow line illustrates the fluctuation in revenue over time.
###### Interpretation: 
Observing the trend helps in identifying seasonal patterns or trends in revenue generation. spikes or dips in revenue can indicate peak or off-peak seasons, respectively. Additionally, steady growth or decline in revenue over time can provide insights into the overall performance of the market.

##### Monthly Trend of Occupancy:
- The line plot shows the average occupancy rate each month.
- The x-axis represents the months, while the y-axis represents the average occupancy rate.
- The green line represents the trend in occupancy rates across different months.
###### Interpretation: 
Analyzing the occupancy trend helps in understanding demand patterns throughout the year. High occupancy rates suggest strong demand, while low occupancy rates may indicate periods of lower demand. Identifying peaks and troughs in occupancy can inform property management decisions, pricing strategies, and marketing efforts.




![download-18](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/20de18db-3605-4e01-880e-f7c2987d1a16)


The visualization above presents the  revenue and occupancy rates across different cities based on the market analysis data.

#####  Revenue by City:
- The left subplot illustrates the average revenue generated in each city.
- Cities are represented on the x-axis, while the average revenue is depicted on the y-axis.
- Each bar represents the average revenue for a specific city, with the height indicating the revenue value.
###### Interpretation:
This plot allows for a comparison of revenue generation across different cities. Cities with taller bars have higher average revenue, indicating stronger financial performance. Understanding revenue disparities among cities can guide investment decisions, marketing strategies, and resource allocation.

![download-19](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/c7b6f48a-331f-430d-b3b8-c5f3a4168ab1)

#####  Occupancy by City:
- The right subplot displays the average occupancy rates for each city.
- Cities are shown on the x-axis, while the average occupancy rate is displayed on the y-axis.
- Each bar represents the average occupancy rate for a specific city, with the height indicating the occupancy percentage.
###### Interpretation: 
This plot facilitates the comparison of occupancy rates across different cities. Higher bars indicate cities with higher average occupancy rates, suggesting strong demand for accommodations. Identifying cities with consistently high occupancy rates can help in prioritizing investment opportunities and optimizing pricing strategies to maximize revenue.



![download-21](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/94eb7aae-b3f6-4d10-bdb6-b18a6b157d98)
The visualization above presents the  revenue and occupancy rates  based on the market analysis data.

##### Revenue by Zipcode :
- The left subplot illustrates the average revenue generated in the top 10 zip codes.
- Zipcodes are represented on the x-axis, while the average revenue is depicted on the y-axis.
- Each bar represents the average revenue for a specific zipcode, with the height indicating the revenue value.
###### Interpretation: 
This plot allows for a comparison of revenue generation among the top-performing zip codes. Zip codes with taller bars have higher average revenue, indicating stronger financial performance. Understanding revenue disparities among zip codes can inform investment decisions, marketing strategies, and resource allocation.

![download-20](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/a2360df9-b462-44f1-a7cf-640dc6f19d62)

##### Occupancy by Zipcode :
- The right subplot displays the average occupancy rates for the top 10 zip codes.
- Zipcodes are shown on the x-axis, while the average occupancy rate is displayed on the y-axis.
- Each bar represents the average occupancy rate for a specific zipcode, with the height indicating the occupancy percentag
###### Interpretation: 
This plot facilitates the comparison of occupancy rates among the top-performing zip codes. Higher bars indicate zip codes with higher average occupancy rates, suggesting strong demand for accommodations. Identifying zip codes with consistently high occupancy rates can help prioritize investment opportunities and optimize pricing strategies to maximize revenue.



![download-12](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/5261d302-3d0b-40aa-a130-5f2aab964dd0)

![download-13](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/93385ec3-3c3c-4ac8-81d8-452ca123f3ab)
![download-11](https://github.com/Deepu2304/Real-Estate-Analysis/assets/86673603/1e6a55e0-ecda-4833-b13d-0ab08901df27)

The scatter plots above depict relationships between different variables in the market analysis dataset:

##### Scatter Plot of Revenue vs. Occupancy:
- This plot illustrates the relationship between revenue and occupancy rate.
- Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the occupancy rate, while the y-axis represents revenue.
###### Interpretation:
The scatter plot allows us to observe how changes in occupancy rates correspond to changes in revenue. Clusters of points with higher revenue may indicate properties with consistently high occupancy rates, suggesting a positive correlation between occupancy and revenue.

##### Scatter Plot of Revenue vs. Nightly Rate:
- This plot showcases the relationship between revenue and nightly rate.
- Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the nightly rate, while the y-axis represents revenue.
###### Interpretation:
The scatter plot helps identify how changes in nightly rates affect revenue generation. Clusters of points with higher revenue at lower nightly rates may indicate properties that attract more bookings due to competitive pricing or higher perceived value.

##### Scatter Plot of Nightly rate vs. Length of Stay:
- This plot visualizes the relationship between Nightly rate and length of stay.
-Each point on the scatter plot represents a specific listing or property.
- The x-axis represents the nightly rate, while the y-axis represents the length of stay.
###### Interpretation: 
The scatter plot allows us to examine how the length of stay influences occupancy rates. Properties with longer average stays may exhibit higher occupancy rates, indicating potential opportunities to target guests seeking extended accommodations.

# Conclusion
The analysis of Airbnb data reveals key insights for property owners and investors. Geographic distribution highlights popular rental areas, while revenue and occupancy trends show seasonal variations with a positive correlation. Property features like hot tubs and pools are prevalent, often with a moderate positive correlation between them. Location-based analysis identifies high-demand areas, aiding investment decisions. Market trends uncover seasonal patterns and guide pricing strategies. Overall, these insights optimize revenue and occupancy rates in the Airbnb real estate market.



