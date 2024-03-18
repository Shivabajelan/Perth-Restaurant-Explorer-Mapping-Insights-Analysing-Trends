# Yelp_Data_Insights_Dashboard
Group members: Shiva Bajelan, Anrie Santos, Jeremy Hooper

Imagine it is a special day, and you just want to go out for dinner. We plan to examine the restaurants of Perth and its suburbs (mainly around the city) and prepare a dashboard showing a map of where they are, what kind of cuisines they have, their rating, their price level, and much more information you need to know. We plan to make choosing your favourite cuisine easy for you and help to create a good experience out of your special day. 

In the other part of this project, by looking at the Yelp data about restaurants and bars in Perth, we aim to perform exploratory data analysis to determine relationships between some different variables.

Research Questions to Answer:

 1. How does the distance of a business from General Post Office (GPO) as a reference point correlate with its rating and review count?
 2. How do different price levels correlate with the number of reviews? What is the impact of price level on customer satisfaction, review counts, and ratings distribution within the restaurant and bar industry?
 3. Does the category of restaurants correlate with the number of reviews?
   
# Usage
Explore the interactive map to see the restaurants data visualised with markers representing name, address, phone number, price level, rating, number of revies, and more information. You also can narrow down your searches from the dropdown menu provided and search whatever your preferences are for eating out. Click on individual markers to get more information about each food businesses.

   
#   Development Workflow for EDA part of project
## Data Source:
* Raw data extracted from Yelp website using their public API
* Data got cleaned and ready for visuailisation and analysis using Pandas
## Backend:
* Clean data transferred and stored in SQLite database for future use
## Frontend:

* Clean data extracted from the database and used for Visualisation and analysis 
* Make query to the backend (SQLite database) to retrieve data for visualisation and creating interactive map created by folium library
## Visualisation:
* Folium, Pandas, Matplotlib, scipy.stats, Ipywidgets
  
# Navigating the Repository
* We created four notebooks for this project:
  1. API_data_extraction.ipynb used for extracting data from Yelp Website
  2. data_cleaning.ipynb for cleaning the raw data
  3. database_operation_and_visualisation.ipynb for housing our clean data in SQLite database and performing EDA analysis
  4. interactive_map.ipynb for creating an interactive map for users to explore their desired place from different places to eat in Perth
   
* Detailed analysis are provided inside the database_operation_and_visualisation.ipynb
   
* The raw data, clean csv, and Excel data by using Pandas are stored in the data directory
* Clean data for interactive map visualisation is located in Resources directory
  
# Note(Jeremy's explanation)

# Ethical considerations in this project

# Data Source
Data for restaurants and bars in Perth from https://www.yelp.com.au/perth

# License 
This project is licensed under the MIT License.
