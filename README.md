# So, how long?

This repository contains the data used for the so-how-long data visualization for the NatGeo 2019 Ocean Plastic Innovation Challenge. 

## List of files
- The files countries.json and NatGeo_Countries.csv were used to construct the bar chart, and include values of ocean plastic pollution for 50 selected countries, along with calculated distances and walking times.
- The files oceans.json and NatGeo_Oceans.csv were used to construct the aggregated oceans plastic pollution data and were constructed by aggregating all countries in our original dataset by their bordering oceans. 
- The NatGeo_Social.json file contains some selected social media posts included in our submission, our full Twitter database is tweets_media_geocoded.csv.
- The map_plastic.topojson file was used to construct the map in our data visualization. 
- The file jambeck_with_oceans.csv contains the original dataset upon which all of our calculations and other data is based (From Jambeck et al. 2014) with some added annotation of bordering oceans for each country.

## List of scripts
- The script bar_chart.R contains code used to prepare data for the bar chart datasets and the map
- The script bottles_anim_data.R contains code used to prepare the bottles animation on the bar chart toggle
- The script data_cleaning.R contains code used to geocode and clean up the raw twitter database
- The script ocean_avg.R contains code used to prepare data for the aggregated oceans visualization
