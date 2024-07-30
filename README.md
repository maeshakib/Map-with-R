# OpenStreetMap-with-R

#install.packages("osmdata") # For getting and working with OpenStreetMap data
#install.packages("ggplot2") # For data visualization

library(osmdata)
library(ggplot2)

# List the features of OSM data
available_features()

We use the function available_tags() and ask for tags for a particular feature. In this case, we will look for the tags of those water features:

available_tags(feature = "water")
