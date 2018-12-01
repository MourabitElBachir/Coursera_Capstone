# The Battle of the Neighborhoods - Week 1

## Introduction :

**Paris** and **New York** are two major economical and multicultural cites. Both cities become a centre of attention for business, job employment, tourism, residential, education, shopping and sports
activity.

This work will be focused on creating and visualizing neighborhood's profiles in boroughs of **Paris** and **New York City**. These profiles will be based on the numbers and categories of venues present in each neighborhood in these cities, classifying each neighborhood based on statistical data and automated analysis using classification algorithms (K-means). Hopefully, these city profiles can give valuable insights about the life and economy of each region, making possible better-informed decision making for business and better public policymaking. Naturally, the target audience of this work are urban planners, policymakers, or urban services business looking to expand. 

## Business Problem :

The main business problem attacked in this work is based on how to determine the optimum location for a new business, a restaurant, bar, or office building. This problem can be solved by means of inferred data about already existing business. Naturally certain types of enterprises tend to be built in the same areas, through economic incentive or public regulations. Data about venue category density in a neighborhood can provide valuable information about **probable new markets** or **regions with low offerings in certain types of service**. It is important to also mention that the inexistence of certain types of enterprises can also mean that there is no demand for their services, indicating that just data about venues, without additional socioeconomic information about the regions, is not sufficient data for constructing a complete picture. Nevertheless, it is possible to construct robust profiles about the urban makeup of the cities, sufficient for kickstarting the plans for new business, and this will be our main goal.

## Data & Tools Description :

This work is about analysing two famous and multicultural cities : Paris and New York City. The boroughs and neighborhoods names and geometric informations of **Paris** are extracted from *Open data website* which provide all the datasets published by Paris city departments and its partners under an **ODbL license**. For **New York City**, the data is provided by the course in previous assignments in a JSON file and the original source of the this dataset exists for free on the website : ***New York University - Spatial Data Reposirtory***. The coordinates will be utilized for map generation, and as input for the Foursquare API, that will be leveraged to provision venues information for each neighborhood. A sample of the venue data extracted with *Foursquare API* calls is showed in the picture below.

We will focus on the venue category parameter, refining and clustering different categories of venues in major groups that will facilitate the analysis and also make possible the generation of better visualizations. Clustering algorithms like K-Means will be used to automatically group the neighborhoods in similar groups. Plotly, *Seaborn* and *Folium* Python packages are used for data rendering and visualization, providing rich graphs and maps.

[1] Open Date for Paris - https://opendata.paris.fr/explore/dataset/arrondissements/information/ : Paris Boroughs data

[2] Open Date for Paris - https://opendata.paris.fr/explore/dataset/quartier_paris/information/  : Paris Neighborhoods data

[3] New York University, Spatial Data Reposirtory - https://geo.nyu.edu/catalog/nyu_2451_34572 : New york Boroughs and Neighborhoods)
