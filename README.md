# Final-Project-Tableau

## Project/Goals
This project for Tableau dives into the New York City airbnb listings of its five distinct Boroughs from the time period of 2008 to 2012. My main goal with this dataset was to visual the average rental prices of airbnb listings based primarly on their neighbourhood location, bed amnenity count, and room type. Along with 
signifying the difference between single-listers and multi-listers for potential renters and investors to answer the following questions.

### 1.Visualizing the average rent throughout New York City could help both potential renters decide where to search for when renting, along with potential investors in what boroughs would have the greatest return for their investments. 
This would however require further research in property prices to make comparisons that I won't be covering in this presentation.

### 2. Indicate the difference between airbnb host IDs that have a single-listing or multi-listings could potentially indicate certain trends, such as the following:.

- Higher saturation of multi-listing hosts can initiate an upward trend in property investors. Causing a higher market saturation and increased competition, potentially driving down prices as these solo investors or companies that specialize in property management enter the market and compete against one another.

- Higher saturation of single-listing hosts can potentially indicate an influx of individuals who are trying to subsidize their yearly income in order to combat economic burdens.
 



## Process
# Step 1: Data Preperation.

I first started with loading in the provided excel file and identify my data types and ensure that certain data types where the either present or formatted correctly such as insuring a geographical data type was present and prices/bed count columns were integer type data so I can create calculated fields in the following steps.
I also needed to make calculated fields to display average rent and host types.

# Step 2: Visualization Planning Creation.

At this stage, I concluded I would need five distinct visualizations to be present on the dashboard to answer my project questions.

  1. A linear line graph displaying the total count of unique hosts as the months go on in the dataset divided by host type.
  2. Another stacked bar graph visualizing the average rent by both room types and neighborhood location. Also with the two different host types present, showing the difference between the two.
  3. Line graph illustrating the average rent of listed properties by bed amenity count.
  4. Sunburst graph showcasing property type distrubution between the three primary room types in the respective five New York City neighborhoods divided by the host type.
  5. Map showcasing the average rent by zipcode in New York City. This map can be filtered on the right side of the dashboard with the beds filter to look for certain average prices in different zip code areas by bed count.

## Results
(Option 2, question 3 [airbnb.xlsx](https://docs.google.com/spreadsheets/d/1BJWyZpZrrRUla_EQ6Pnusy0KH31UMGf2/edit?gid=180839496#gid=180839496) 

My main question was 
*** How does the average rent across New York City's five neighbourhoods vary, and how can this information help both investors and rents make informed choices?***
The visualizations I created served their following purposes.

### Cumulative host count over time
Analyze the markets competition, displaying the growth rate of both single-listing hosts and multi-listing hosts giving insight of the evolution of the market.

### Rental price per bed count by room types
Analyze the average rent by room type and bed count. Can be filtered by neighborhoods to display data for specific neighborhoods.

### Average rent 
distrubution of average rent by room type and neighborhood.

### Distrubution of room type by neighbourhood
Sunburst chart showcasing all listings by the hierchial data of neighborhood, then room type. Can also be filtered to display room types by a specific bed range.

### Map 
Symbol map visualizing the average prices throughout New York City. Can also be filtred by room type and bed count.


To reiterate, my main question was the visual the average rent in new york city and see what locations had the lowest vs highest cost for renters and thus in the same context, lowest vs highest yield for investors.

With the results.
- I concluded that Staten Island entire homes/apartments had the highest average rental cost between both single listers and multi listers combined.
- There is a much larger host count of single-listing hosts vs multi-listing hosts even when taking into consideration the total listing
- The lowest average rental price by bed count for single listers and multi listers were both in the shared rooms category. Specifically Single-Listed 6 beds at an average price of 35, and Multi-listed 4 beds at an average price of 39.
- The largest distrubution of listings were located in Manhatten, with the majority being listings for entire homes and/or apartments. While Staten Island had the smallest distrubution of listings.

## Challenges 
My initial questions wanted to see the listing date of each specific room but had to be ultimately scrapped cause said data was missing from the dataset.
I also discovered some of the geographical data was inaccurate, presenting slightly bias data in certain sectors.


## Future Goals
If I was given more time, I would go back and furher clean the data by fixing geographical data, ensuring that all zip codes correctly matched their corresponding neighborhood. Look into incorporating additional datasets on either property listings and/or rental market data to get a better understanding on potential 
returns for investors.
I could also look into making a regression model to forecast the increased growth of listings or rental increases.
