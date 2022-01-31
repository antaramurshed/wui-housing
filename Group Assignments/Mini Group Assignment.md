# California Wildfire Incidents and Housing Demographics

Here is the [link](https://github.com/antaramurshed/wui-housing/blob/main/Group%20Assignments/Project%20Proposal.md) to the original project proposal. 

## Roles  

Jessica: Working mainly with the with wildfire incidents dataset
Antara: Exploring ACS data and finding structure data on OSM


## Status update: 

We were a little bummed about not being able to use the UWI dataset but we’ve found a way to still include it in our narrative. We still have to get through the housing and income census data. We are a little worried that we don’t have data that tells a more spatial story. The wildfire incidents data is just points on a map. We may try to include one more dataset. 

We are considering using OpenStreetMap to look over historical (meaning 2017-2020) structure data to compare what structures have existed before and after wildfire incidents. We have been using Census Reporter to look into housing, income, and racial data for Santa Rosa and San Jose Metropolitan Statistical Areas (MSAs) but have found that the datasets sometimes contain data that go outside the defined MSA. 

## Data update: 

Initially, much of our analysis focused on using Wildland Urban Interface (WUI) spatial data, however all the WUI data we have found is too large to use on JupyterHub. We may still use WUI maps to inform our analysis but we will not be using WUI spatial data with python. 
We have [wildfire incident data](https://www.kaggle.com/ananthu017/california-wildfire-incidents-20132020) from 2013-2020 we have been exploring and it seems promising. The dataset provides us with data points like the number of acres that have been burned in a single wildfire and the number of structures that have been destroyed or damaged. So far we have only gone through census reporter data on housing tenure in each MSA. The links to that data are here: 

[San Jose Occupied Housing Data](https://censusreporter.org/data/table/?table=B25003&geo_ids=140%7C31000US41940&primary_geo_id=31000US41940#) 

[Santa Rosa Occupied Housing Data](https://censusreporter.org/data/table/?table=B25003&primary_geo_id=31000US42220&geo_ids=31000US42220,04000US06,33000US488,01000US)


## Concerns:

Major concerns: 
Not having a strong consistent narrative regarding wildfire incidence and housing justice. We are continuing to do data exploration but there is a concern that what we are looking into won’t have a cohesive narrative. 
Finding datasets that are the appropriate size to use in JupyterHub/not finding enough data

Minor concerns: 
Keeping the geographic scale and comparisons of study areas consistent with each other.  In example, we are currently using ACS defined MSAs to explore demographic profiles but the dataset includes data outside of the MSA. Other datasets we use could also be organized by county or city when we are looking by MSA. 
Not having relevant housing data. Neither the wildfire incidents dataset nor the census reporter have the data on how many residential structures were destroyed or damaged. We are also interested in how much has been rebuilt in the aftermath of the wildfires but that may be too late to include in the project.



