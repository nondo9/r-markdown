# r-markdown
library(leaflet)

my_map <- leaflet() %>%
  addTiles() %>%  
  addMarkers(lng=7.68465, lat=45.0432, popup="Salsa Rossa - Really good pizza in Turin")
my_map 
