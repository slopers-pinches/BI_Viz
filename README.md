# BI_Viz
Personal BI Visualization Projects 


## Dashboards

1) [***Top 10 Countries by Player Value in English Football***](https://github.com/slopers-pinches/BI_Viz/tree/main/Top%2010%20Countries%20by%20Player%20Value%20in%20English%20Football%20Project)

[Link to Dashboard](https://public.tableau.com/views/Top10CountriesbyPlayerValueinEnglishFootballDashboard/Top10CountriesbyPlayerValueDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)

![Top 10 Countries by Player Value in English Football](https://user-images.githubusercontent.com/71954989/176973841-62f19c60-21b3-4d6b-8942-f94ebb1e64d0.gif)


**Summary**:

On Tableau, I created a dashboard to illustrate the top 10 countries of players playing in English football leagues (English Premier League, English Championship, League 1, etc.) by players' values. The dashboard is interactive where a user can see where highly valued players are from and what club they are playing for during 2018-19 season. The data is a collection from several data sources.

Here are the key highlights I learned when building the Tableau dashboard:
  * Import an Excel workbook, PDF file, and KML file
  * Create the main data source by unionizing the 2 worksheets from the Excel workbook and join (left join) the data tables from the PDF file
  * Conduct data pre-processing and mainpulation via calculated fields method (e.g. split columns, alias data, change data types, etc.) in the main data source
  * Combine the main data source to spatial file (KML file) through data blend method to create a choropleth map
  * Create a set for the choropleth map to show the Top 10 Countries by the sum of players' values by country
  * Create a crosstab to show a table of Clubs, Players' Name, and Players' Value from the choropleth map
  * Format the choropleth map and crosstab table
  
  
