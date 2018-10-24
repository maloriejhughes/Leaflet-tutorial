# Leaflet-tutorial




Install the required packages by running the following R command: 

```{r} 
install.packages( c("leaflet"
                   ,"readr"
                   , "markdown"
                   , "tidyverse"
                   , "rgdal"
                   , "geojsonio"
                   )) 
```

The DC neighborhood cluster demographics dataset was found here: 
https://data.world/codefordc/dc-neighborhood-cluster-demographics


The DC neighborhood cluster geojson file was found here: 
http://data.codefordc.org/dataset/neighborhood-clusters



Someone asked me how to get the pop-ups to show on hover rather than click.  The short answer is: to show on hover, you want a ```label``` instead of a ```popup```.  I will add a section for that, but for now, look here for the detailed answer and an example: https://rstudio.github.io/leaflet/popups.html  

                  
