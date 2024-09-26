# aviation-accident-project
## overview
In this project, we will work with aviation accident data stored in a CSV file, AviationData.csv. Our goal is to load, clean, and analyze the data to identify patterns in accident causes, severities, and other important metrics. For this task, we'll need libraries to handle data processing, cleaning, and visualization. We will utilize:pandas for data manipulation and cleaning. NumPy for numerical operations. matplotlib and seaborn for data visualization.

## Business understanding
company is expanding in to new industries to diversify its portfolio. Specifically, the company is interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. I am charged with determining which aircraft are the lowest risk for the company to startOur this new business endeavor. The key business questions are:

1.how many accidents occurs per year.?

2.how may accidents occurs due to weather condition?

3.is there big number of fatal injuries per accident?

4.which engine type has more accidents?

5.which type of aircraft has more accidents?

6.how many people survi
## Data understanding and Analysis
The dataset used for this analysis is a dataset from the [Kaggle National Transport Safety Board](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) webiste which is based on records of aviation accidents, which are 88,889 in number and span across 31 columns. Data includes accident dates, locations, injury severity, damage to aircraft, and more.
### Find from data analysis
#### 1.how many accidents occurs per year.?
he following bar plot shows the number of accidents that occurred each year.
A decline in certain years can be indicative of improvements in safety regulations, technological advancements, or other external factors like increased/decreased air traffic. If a trend is visible (e.g., a steady decline over the years), it could suggest that aviation safety has improved. Alternatively, sudden peaks in accident frequency might warrant a deeper investigation into specific events or patterns during those years.
#### 2.how may accidents occurs due to weather condition?
This line plot displays the number of accidents caused by different weather conditions.
Some weather conditions, such as clear or cloudy skies, may be more frequently associated with accidents simply because they occur more often. If severe weather conditions like thunderstorms or fog are highly represented, it could highlight the dangers of flying in adverse weather. This plot could also reveal gaps in weather forecasting or a need for better training and equipment for flying under adverse conditions.
#### 3.is there big number of fatal injuries per accident?
A pie chart representing the number of total fatal injuries per accident.
If the majority of accidents result in low or zero fatal injuries, this could indicate that most accidents are not severe or that modern aircraft are becoming more survivable. A significant proportion of accidents with high fatalities would highlight more catastrophic events, which may call for further analysis into the causes and prevention strategies. This information is crucial for safety regulators focusing on reducing fatalities through better equipment or emergency procedures.
#### 4.which engine type has more accidents?
This scatter plot visualizes the number of accidents categorized by engine type.
Certain engine types may show higher accident frequencies, which could suggest they are more prone to failure, or simply that they are more commonly used. By identifying trends across engine types, manufacturers and airlines can prioritize safety improvements or reconsider the use of particular engine models. Correlations between engine types and accident frequency can also guide maintenance practices and inspections.
#### 5.which type of aircraft has more accidents?
A bar chart showing the number of accidents for the top 20 aircraft manufacturers.
A manufacturer with a high number of accidents could either have a large fleet or be producing aircraft that are more prone to incidents. Manufacturers with lower accident numbers may have better safety records or produce aircraft that are more reliable or less commonly used. Further breakdown of the data by model could provide deeper insights into specific designs that may require attention.
#### 6.how many people survi
This scatter plot represents survival analysis, counting injury severity based on the number of engines in the aircraft.
The number of engines may influence the severity of an accident. For example, twin-engine aircraft may be more likely to avoid catastrophic failure compared to single-engine planes, leading to lower injury counts. Aircraft with more engines could offer redundancy in case of failure, improving chances of survival. This analysis could be useful for regulatory bodies when setting standards for engine redundancy or for airlines when considering fleet compositions.

# Conclusion
Safety Performance: Choose models with a demonstrated decline in accidents over time and a high survival rate in case of accidents. Engine Reliability: Opt for aircraft with reliable engines and, where possible, select twin-engine or multi-engine planes to improve redundancy. Manufacturer Reputation: Favor aircraft from manufacturers with strong safety records and fewer accidents overall. Weather Adaptability: Aircraft with proven performance in adverse weather conditions are highly recommended, especially for operations in regions prone to severe weather. By focusing on these factors, you can significantly reduce risk and ensure safer and more reliable aircraft operations.
# Tableau visualizations
[https://public.tableau.com/app/profile/john.louis.kirigo/viz/Aviationdata_17273383624390/Dashboard1?publish=yes](URL)
