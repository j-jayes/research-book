# Visualization tools




## Swedish regional growth dashboard

To visualize and make interactive some of the data that Prof. Enflo has collected on regional GDP and population in Sweden, I built [this little dashboard](https://jonathan-jayes.shinyapps.io/swedish-regional-accounts/). You can see a screenshot below.

<img src="C:/Users/User/Documents/Recon/research-book/resources/09-viz-tools/images/swedish-regional-accounts.png" width="854" style="display: block; margin: auto;" />

## House price explorer

Fredrik Kopsh has a project on rental prices in Stockholm in the first half of he 20th century. I made [this data explorer](https://jonathan-jayes.shinyapps.io/ames-house-explorer/) as a proof of concept for what a tool to explore his collected data might look like.

This iteration uses data from the [Ames Housing dataset](http://jse.amstat.org/v19n3/decock.pdf) that you can access [from Kaggle here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). 

It comprises a `leaflet` map with dots showing each house in the dataset. Red dots indicate higher sale prices. There is an HTML popup on each dot that shows information about the house, including sale price, lot area, and . Two additional plots show a scatter of sale price against continuous variables like year built, lot area, and living area, as well as a ridge plot showing the density of price by a selection of categorical variables including building type, exterior material, and the number of rooms. Further, there is a date range input to filter the dataset.

<img src="C:/Users/User/Documents/Recon/research-book/resources/09-viz-tools/images/ames-housing-explorer.png" width="780" style="display: block; margin: auto;" />

