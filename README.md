1. Data Profiling: Using Alteryx, I conducted data profiling to understand the data's structure and quality, identifying issues like missing values, duplicates, and inconsistent date formats. Documenting these inconsistencies was essential for maintaining data governance and ensuring high data quality
2. Dimensional Model: To effectively organize, query and visualize the data ensuring high performance and data quality for impactful analysis did using ER studio. Most importantly, dimensional model supports ETL processes (which brings us to our next step and that is data integration) by clearly defining how data should be transformed & loaded into our database tables.
3. Data Integration: Began by loading the raw data into staging tables to separate it from the final integrated schema. This approach allowed us to conduct thorough data cleaning and transformations without affecting the original data. Using Talend, we performed various cleaning tasks, such as standardizing data types and unifying the violation columns from both datasets (Chicago's single violation column and Dallas's 25 violation columns) into a consistent format. We used tmap in all our workflows to define mapping rules and conditions for instance, changing the data type, concatenating fields or entering regular expressions. After cleaning, we loaded our data into our respective facts and dimensions tables. -- This ensures that only high-quality, consistent, and fully transformed data is integrated into the final schema key aspects of data governance. 
Additionally, we connected tableau to our relational database to enable real time querying of the integrated data.
4.BI Reporting: Crafted data-driven visualizations using both powerbi and tableau

Time-Based Analysis for Crashes: Visualizing crash trends over different times of the day, week, and year to identify peak accident periods.
Accident Reports:
Pedestrians Involved in Accidents: Detailed fatality analysis involving pedestrians.
Top 10 Contributing Factors: Identifying the most common factors leading to crashes.
Top 5 Areas with Most Crashes: Highlighting the areas with the highest crash frequencies.
Top 5 Areas with Most Fatalities and Injuries: Focusing on regions with severe outcomes.
Top 5 Vehicles for Most Crashes: Analyzing vehicle types most frequently involved in crashes.

City-Specific Dashboards:
New York
Austin
Chicago
