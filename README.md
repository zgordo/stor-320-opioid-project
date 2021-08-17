

# stor-320-opioid-project

<h2>Summary<h2>
<p>This was a the my final Project for STOR 320 at UNC Chapel Hill. My group explored opioid deaths by county in 2016.
   We looked at a number of different factors including population, education, income, GDP, political leaning, and many others. We got the data from https://www.kaggle.com/ryanandreweckberg/opioid-crisis-by-interpersonal-relationships.
   As a group we performed basic statistical modeling and visualized using R Markdown and Tidyverse. We also used some 2016 election data from MIT. Unfortunately this data no longer exists in its current form, and I don't have the downloaded data on my computer. This means I cannot knit the final markdown to display the final product. However I have included the HTML and RMD files for my contribution. The code for the entire project can be found in Final_Report_Group_11.<p>

<h2>My Role<h2>
<p> My Role in the group was to design a linear model, perform data cleaning, and build an interactive map with leaflet. I selected the linear model using backwords selection. This means I started with all of the features we wanted to look at, then removed the feature with the highest p-value, if the adjusted R^2 increased I repeated the process. For the map I used the Leaflet library. It displayed the number of deaths and the deaths per capita in each county in 2016. The Leaflet Map can be found in opioid_map.html and opioid_map.rmd. my other contributions can be found in finalcode.html and finalcode.rmd. <p>
