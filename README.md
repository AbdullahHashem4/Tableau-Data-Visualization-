# Tableau Data Visualization Projects 💹 
## Global Tech Experience Internship - Tableau Analysis

**1. UNESCO Dataset:✅** 
In this project for Tableau, I analyzed a dataset containing UNESCO's world heritage sites, categorizing them as cultural, natural, or mixed. Utilizing Tableau, I visualized the data findings across multiple sheets. 
- Sheet 1, I created a bar chart illustrating the distribution of heritage sites by type. 
- Sheet 2 presented a stacked bar chart showcasing the number of sites on the danger list for each category, distinguishing between endangered and non-endangered sites. 
- Sheet 3 featured a side-by-side bar chart further breaking down endangered and non-endangered sites by category. 
- In Sheet 4, I identified countries with the largest numbers of heritage sites through a sorted bar chart. 
- In Sheet 5, I depicted the countries with the largest physical areas dedicated to heritage sites. For a more detailed analysis, an optional LevelUp task focused on France's heritage sites, where I created a bar graph showing the total area in hectares for each site, with tooltips providing additional information on category. Finally, I addressed scaling issues by adjusting the Area Hectares axis to logarithmic in order to better represent the distribution of smaller sites alongside larger ones.

**2. Forbes Dataset:✅**
In this project focused on creating foundational charts using Tableau, I utilized a Forbes dataset detailing the earnings of top celebrities from 2005 to 2020, particularly examining the gender pay gap among actors and actresses. 
- In Sheet 1, "Yearly Actor Earnings By Sex," I recreated a side-by-side bar chart displaying the total earnings by gender for each year from 2016 to 2020, filtering by gender (male and female) and category (actors and actresses), while also creating a tooltip to display the number of actors or actresses for each bar. 
- In Sheet 2, "Actor Earnings By Sex," I compared the average compensation of actors and actresses through a bar chart with corresponding filters. 
- In Sheet 3, "Highest Paid Actors," I created a horizontal bar chart showcasing the top 10 highest-paid actors and actresses, colored by gender, and answered questions regarding the gender distribution within this list.
- In Sheet 4, "Celeb Earnings Over Time," I visualized the trend of average earnings for actors and actresses over the years using a line chart, analyzing whether the pay gap widened or narrowed. 
-For the LevelUp task, I constructed a stacked bar chart of total earnings per celebrity category, identifying whether certain categories were dominated by one gender.

**3. Multifaceted Dataset:✅**
In this project focused on basic visualizations using Tableau, I worked with three diverse datasets: one detailing adult male and female heights by country, another tracking music sales from 1973 to 2019, and a third focusing on global video game sales.
- Sheet 1 visualized countries with male average heights exceeding the world average.
- Sheet 2 replicated this analysis for female heights, identifying a unique gender disparity in South American countries.
- In Sheet 3, I charted the total music sales over the years, pinpointing the peak sales volume.
- Sheet 4 showcased a stacked bar chart depicting total music sales by year and format, highlighting dominant formats in specific years.
- Sheet 5 featured a sorted bar chart revealing the three video game genres with the highest total global sales. 
-Additionally, LevelUp tasks on Sheets 1 and 2 explored alternative visualization techniques for height data, offering insights into countries with taller or shorter women compared to the global average.

**4. UFO Sightings Dataset:✅**
In this project I focused on calculated fields within Tableau, I worked with two datasets: one detailing UFO sightings by state and another by country, aiming to discern patterns in UFO encounters, including timing, duration, and shapes.
- In the UFOSightingsByState sheet 1, I extracted state codes from the Location column and capitalized them to create a custom calculated field, subsequently visualizing the number of UFO sightings by state in a descending bar chart, with the top three states being answered in the Questions sheet.
- Moving to the NumberSightingsPerCountry sheet 2, I extracted country codes and capitalized them, then presented a text table displaying the total sightings per country, with the number of sightings in the United States answered in the Questions sheet.
- On the UFOSightingsLengthByMonth sheet 3, I calculated the length of UFO encounters in minutes, creating a bar chart of average encounter lengths per month, with the months of longest sightings answered in the Questions sheet.
- Shifting to the UFOSightingsByShape sheet 4, I capitalized UFO shape descriptions and visualized the most commonly encountered shapes in a descending bar chart, with the most common shape answered in the Questions sheet.
- Finally, in the UFOSightingsByHour sheet 5, I visualized the number of UFO sightings by each hour of the day, with the most popular sighting time answered in the Questions sheet. 
- For the LevelUp task, I converted descriptions to lowercase, identified prevalent UFO colors through conditional statements, and created a bar chart showcasing the most common UFO colors, with the dominant color answered in the Questions sheet.

**5. Super Bowl Dataset✅**
In this project I focused on Super Bowl analysis, I tackled questions surrounding the annual American football spectacle using three datasets: superbowl_scores, tv_ratings, and halftime_shows.
- First, I joined these datasets, inspecting columns to determine the appropriate fields for joining. 
- Next, I created a calculated field called Year to compute the year of each Super Bowl game, enabling visualization of the average household rating over time through a line chart.
- Subsequently, I categorized Super Bowl games as nail-biters, close games, or blowouts by creating calculated fields based on score differences, and visualized the distribution of game types through a bar chart.
- Additionally, I analyzed trends in advertising effectiveness by plotting the average ad cost over the years and examining the relationship between ad cost and household ratings.
- For the LevelUp task, I visualized the popularity of halftime musical acts and determined the most common game types among top-viewed performances, as well as the average viewership by game result type. These analyses provided insights into Super Bowl viewership trends and the effectiveness of advertising strategies over time.

**6. NYC Green Taxi Dataset✅**
In this  project centered on New York City taxi data analysis, I delved into various aspects of taxi usage and costs, utilizing calculated fields to enhance the dataset's usability. 
- Beginning with mapping numeric rate codes to interpretable strings, I created a calculated field named Rate Type.
- Following this, I visualized the distribution of fares using a histogram, describing its shape and identifying common fare ranges.
- Integrating Rate Types as color encoding, I discerned the most common type of trip and investigated anomalies, particularly a peak in fares around $52-$54, potentially linked to trips to JFK airport.
- Confirming these observations through a sorted bar chart of trip counts per Rate Type, I then examined the average trip distance for each Rate Type, identifying categories resulting in longer trips on average.
- Further analysis focused on tipping trends, where I calculated Tip Per Distance to assess tipping amounts per mile traveled and identified which trip types garnered higher tips.
- For the LevelUp task, I expanded analysis to include histograms of tip-subtotal ratios across all trips, examining payment types and common tip percentages relative to fares.

**7.  BillBoard Spotify Hits Dataset✅**
In this project milestone for Tableau, I focused on creating interactive visualizations using parameters and explored two datasets: BillboardHot100 and Spotify songAttributes. 
- In Part 1, I examined the relative popularity of pop and rock genres over time from the BillboardHot100 dataset. I created calculated fields to determine the proportion of pop and rock songs and visualized their trends with a line chart on the Rock and Pop Popularity Sheet. Analyzing the patterns and trends in listener preference for these genres over two decades, I provided insights in the Questions sheet.
- In Part 2, I developed an interactive chart allowing users to select a genre and view its popularity over time, using the SelectGenre parameter to dynamically display the selected genre's proportion in the Top 100. Additionally, I ensured chart presentation by revising the vertical axis to display percentages and making the chart title dynamic.
- For the LevelUp task, I explored relationships between pairs of musical properties using parameters like SelectAudioX and SelectAudioY. By creating scatter plots on Sheet 3 (Audio Features) and converting them into density maps, I visually inspected correlations between attributes like Valence and danceability, providing insights into the strength of these relationships.





