## Project 3 - Visualisation Stream 

### Perth Restaurant Explorer: Mapping Insights & Analyzing Trends

### Shiva BAJELAN, Anrie SANTOS, Jeremy HOOPER

### Introduction

Imagine it is a special day, and you want to go out for dinner. We have examined 532 different restaurants in Perth and their surroundings and prepared an interactive map showing where they are, their cuisines, ratings, price levels, and the information you need to know to play your special day out.

We plan to examine the restaurants of Perth and its suburbs (mainly around the city) and prepare a dashboard showing a map of where they are, what kind of cuisines they have, their rating, their price level, and much more information you need to know. We plan to make choosing your favourite cuisine easy for you and help to create a good experience out of your special day. 

In the other part of this project, we looked at Yelp data about restaurants and bars in Perth and performed exploratory data analysis to determine relationships between some different variables.

### Research Questions to Answer

We posed the following questions:

 1. How does the distance of a business from the General Post Office (GPO) as a reference point correlate with its rating and review count?
    
 2. How do different price levels correlate with the number of reviews? How does price level impact customer review counts and ratings distribution within the restaurant and bar industry?
    
 3. Does the category of restaurants correlate with the number of reviews?
   
### Data Source

We obtained our data set from Yelp, using its publicly available API restaurants data set. Yelp must first approve a person's application to download data before they can do that. The data are public and are free for educational purposes such as our project. Anrie Santos arranged the downloading of our data set.

The data were messy, with some columns containing lists of dictionaries, and data not uniformly entered. Shiva Bajelan did most of the cleaning with some help from Sean Whitehead.

Jeremy Hooper started work on creating the interactive map before the data set was cleaned. He did some cleaning by hand to ensure that this dataset was ready for mapping. Thus the data used for the interactive map has some minor differences to the dataset used in the other analyses.

### Ethical considerations in this project

When conducting a data analysis project on restaurants in your hometown, it's important to consider several ethical considerations carefully. Privacy and anonymity are paramount; ensuring that personal data, potentially linked to restaurant owners or patrons, is is private and anonomous protects individuals. Accuracy in representing restaurant ratings, pricing, and locations is also crucial, as inaccuracies can unfairly affect a restaurant's reputation. Additionally, consider the origins of your data and whether the restaurants consented to their information being utilized, which respects their rights and intentions.

The potential impact on small businesses is another significant concern. It's important to approach the analysis with sensitivity to how it might influence local, especially family-owned, establishments. This involves maintaining a balance in portraying diverse types of restaurants without bias towards certain cuisines, pricing, or locations, thereby ensuring a fair representation of the community's dining options. Also, the accessibility of your visualizations is critical, ensuring they can be understood by a broad audience, including those with disabilities.






### Workflow for Exploratory Data Analysis part of the project

1. Raw data extracted from Yelp website using their public API

2. Cleaned Data and made it and ready for visuailisation and analysis using Pandas and some cleaned by hand for the interactive maps section.

3. The clean data was transferred and stored in SQLite database for future use in the project.

### Navigating the Repository

We created four notebooks for this project:

  1. API_data_extraction.ipynb used for extracting data from Yelp Website,
 
  2. data_cleaning.ipynb for cleaning the raw data,
      
  3. database_operation_and_visualisation.ipynb for housing our clean data in SQLite database and performing EDA analysis,
     
  4. Yelp_Restaurants.ipynb for creating an interactive map for users to explore their desired place from different places to eat in Perth.
   
  5. Detailed analysis are provided inside the database_operation_and_visualisation.ipynb
   
  6. The raw data, clean csv, and Excel data by using Pandas are stored in the data directory

  7. Clean data for interactive map visualisation is located in Resources directory



# Usage
Explore the interactive map to see the restaurants data visualised with markers representing name, address, phone number, price level, rating, number of revies, and more information. You also can narrow down your searches from the dropdown menu provided and search whatever your preferences are for eating out. Click on individual markers to get more information about each food businesses.

   
#



* Clean data extracted from the database and used for Visualisation and analysis 
* Make query to the backend (SQLite database) to retrieve data for visualisation and creating interactive map created by folium library
## Visualisation:
* Folium, Pandas, Matplotlib, scipy.stats, Ipywidgets
  



# Data Source
Data for restaurants and bars in Perth from https://www.yelp.com.au/perth

# License 
This project is licensed under the MIT License.
