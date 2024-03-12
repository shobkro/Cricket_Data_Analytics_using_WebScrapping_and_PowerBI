# Cricket Data Analytics 

The Cricket Data Analytics🏏 project is made on T-20 Cricket World Cup Data. I have used Power BI for making the Dashboard. We can easily analyse the data of the matches played in the world cup. We can also choose our best playing 11 from the pool of players playing the world cup.

To interact with the dashboard you can download the pbix file from the repository and open it in Power BI Desktop locally.

# Data Collection
The data is collected using BeautifulSoup (bs4) to scrape data from ESPNCricinfo for match details, batter details, bowler details, and player details, and images from T20 World Cup. The data is collected in the form of a dictionary and then converted to JSON. The JSON files are then loaded into the Data Preprocessing.ipynb file, where data preprocessing is performed using pandas, and respective dataframes are created. The dataframes are then converted to CSV files that are loaded into Power Query and DAX for data modeling.

# Technology Used
- Python 3
- BeautifulSoup (bs4)
- Pandas
- NumPy
- Data Modeling
- Power Query
- DAX
- Power BI

# Methodology
- Data collection and cleaning
- Exploratory data analysis
- Feature engineering
- Model selection and training
- Model evaluation and validation

# Steps involved in the project:
1) 📝Requirement Scoping
2) 🌐Data Collection using Web Scraping from ESPN Cricinfo website
3) 🧹Data Cleaning and Preprocessing in Pandas
4) 🪄Data Transformation in Power Query
5) ⚒️Data Modelling and Building Parameters in Power BI using DAX
6) 📊Building the Dashboard in Power BI

# Screenshots of the Dashboard

![power_hitters_and_openers](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/ee1c0268-eec7-44f7-8a5c-7369a385e9b8)

![hover_effect](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/9d99bdb6-4926-438d-a2dc-2205d9186a48)

![individual_stats](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/7007a375-aab2-4293-9fc0-d3bd35fd9415)

![anchors](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/5a6911f8-b39b-4ee2-9189-86fc76b36690)

![finishers](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/1bb13a90-5dd5-4ad3-b02c-26de7f52ff4b)

![all_rounders](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/d3fc1aae-129f-4163-a1ab-209e3540d547)

![fast_bowlers](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/7ffd3fd0-aa2f-4736-8d50-a9e39bc02240)

![pick_final_11](https://github.com/shobkro/Cricket_Data_Analytics_using_WebScrapping_and_PowerBI/assets/39133098/ec43f2c2-123c-4cd0-9221-adc860598b07)
