# DDL_USGS_project
<h4>Visualizing rare earth element (REE) deposit locations and mining operations</h4>

<h4>Goal:</h4>
REEs are heavily used in smartphones, general consumer electronics and magnets. Experts predict a shortage of some of these elements over the next years, giving increasing consumption (http://energy.gov/sites/prod/files/edg/news/documents/criticalmaterialsstrategy.pdf) . <br>
It is therefore of interest to learn more about the locations of REE deposits and the success of ongoing mining operations as well as to determine which factors could predict the location of REEs.

1) folder: "REE_actual_mining_choropleth_map"

Download the folder with all the files and run the file "server.R" in R-Studio, setting the working directory 
to the folder.
Creates a world map visualizing the ongoing mining projects/ country and provides summaries of the REE tonnage mined as
well as the top 5 projects/ country. Data was scraped from the webpage http://www.techmetalsresearch.com.

2) folder: "REE_locations_and_deposits_map"

Download the folder with all the files and run the file "server.R" in R-Studio, setting the working directory 
to the folder.
Creates a world map visualizing locations of 15 types of REE deposits and summarizing the number of projects/ country. The user can indicate via a checkbox which element is of interest. Data was obtained from http://pubs.usgs.gov/of/2002/of02-189/

3) folder: "REE_predictive_models"

Contains data files that were prepared to undertake predictive modelling


R version 3.2.1

DDL_USGS_project is licensed under the MIT License. See the LICENSE file in this directory for the full license text.
