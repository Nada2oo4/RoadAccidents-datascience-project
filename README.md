# RoadAccidents-datascience-project
This project investigates how vehicle speed, road surface friction, road types, weather conditions, 
and junction types influence the number of vehicles involved in accidents and emergency response times,
using a combination of a real-world dataset and scraped supplementary data.
Objectives:

Analyze the relationship between:
Vehicle speed and road surface friction
Road types and number of vehicles involved
Weather and road conditions vs. emergency response time
Visualize trends and patterns to answer questions like:
Do slippery roads with low friction and high speeds lead to more multi-vehicle crashes?
How do weather and road types affect emergency response times?

 Web Scraping :

To enrich the dataset and support deeper insights, we implemented web scraping to collect additional information such as:

-Road condition updates or accident reports from traffic authority website
 Libraries Used:

-requests
-BeautifulSoup
-pandas
Scraped data was cleaned and merged with the original dataset to better evaluate real-time impact of weather 
and surface conditions on accident severity.

 Visualizations

Heatmap: Shows how speed and friction affect multi-vehicle crashes.
Scatter Plot: Explores relationship between vehicle speed, friction, and accident size.
Box Plots:
Vehicle speed across road types
Emergency response time across weather and road types

Data Preparation

Cleaned and encoded missing values
Categorized speed and friction into meaningful ranges
Removed unnecessary columns for focused analysis

Tools Used

Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook
Web Scraping: BeautifulSoup, Requests

 Key Insights

Accidents involving more vehicles are more likely on slippery roads at higher speeds.
Emergency response times tend to be longer during bad weather and on rural roads.
