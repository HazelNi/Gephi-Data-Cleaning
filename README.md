# Gephi-Data-Cleaning
## Data to create the Gephi file for Columbia Center on Sustainable Investment/EDF Net-Zero Initiatives Network Graph
This repo includes all the files that's used to create a nodes list and an edges list to feed in Gephi
###### Nodes List: 
Gephi only takes input with a node list starting with ['ID','Label',...] as column headers, and the time slider function to work, it needs to be in a column called 'Timestamp' with vectors of all the years that the node is in existence. For instance, for a node crated in 2019 and is still in existence today, it will have [2019, 2020, 2021, 2022] as its Timestamp value.
###### Edges List: 
Gephi only takes input with a node list starting with ['Source','Target','Type','Weight',...] as column headers, for all the years that an edge exists, it should have a correponding 'Timestamp' in the same format like [2019, 2020, 2021, 2022]. It is assumed that for two nodes that are connected, the edge is established in the same year as the later node is created. 
