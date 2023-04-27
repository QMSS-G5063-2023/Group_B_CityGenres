# City Genres  
## Group B  
Jintong Yu jy3246@columbia.edu  
Xianfeng Jiang xj2292@columbia.edu  
## Project Description  
We are interested in exploring commonalities of 180 travel destinations suggested by Priceline.com and what attributes make some of them more similar than others, with the aim to improve the recommendation system for online travel platforms. To provide evidence of attributes for these destinations, we will collect random facts in terms of travel activities and other descriptive features using various online sources, and scrape documents from reliable websites. Then, we will use hierarchical clustering to find subgroups among these destinations. Making use of the collected data, we expect to explore the question from the perspective of destinations’ attributes recorded in a tabular format, destinations’ general description derived from scraped documents, and combination of the former two perspectives.  

* Tabular Attributes: What are the most common attributes and travel activities among the selected travel destinations? Are there more metropolises or destinations with more natural scenes? How would you divide these destinations into some “marketable” groups?  

* General Description: What attributes extracted from the documents are the most prominent among the selected travel destinations? How many representative attributes are there for defining these destinations into meaningful groups?  

* Combination: Overall, what representative attributes would you choose for dividing these destinations into some “marketable” groups? Describe each group.   

## Data Source   
1) TripAdvisor: We will web scrape the “Brief Introduction” section on the main page and the tags of the top 30 attractions by popularity on the “Things to do” page for each destination.  
2) Wikipedia: We will also web scrape all paragraphs from the Wikipedia page for each destination.  
3) Random facts will be manually recorded in a table based on information provided by TripAdvisor and Wikipedia.  

## Visualizations  
* Map: Visualize the geographic locations of the 180 travel destinations on a world map using leaflet. By adding clusters to the map, users could easily identify the geographical similarity among destinations. We will also notify the representative attributes for each destination in its pop-up.   
* Scatterplot: Display clusters (groups) of data points (destinations) based on the tabular data and text data.  
* Word Cloud: Plot the most common words used to describe these destinations.  
* Bar Chart:  
    1) Plot the most common bi-grams used to describe these destinations.  
    2) Plot the frequency of each defined attribute and travel activity among all destinations based on the tabular data.  
* Interaction: By clicking the button representing a specific group, users could see the corresponding word cloud or bar chart that demonstrates the representative attributes for that group.
