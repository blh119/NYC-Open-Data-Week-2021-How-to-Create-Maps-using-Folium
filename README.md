# NYC-Open-Data-Week-2021-How-to-Create-Maps-using-Folium

This is the repository for NYC Open Data Week event How to Create Maps using Folium. This event is taking place on Friday, March 12, 2021 at 7pm. This repository includes, the datasets, shapefiles, and the IPython workbook needed for this event. 

This project gives a short guide on how to create maps using Python GIS packages including GeoPandas, Shapely, and Folium. It goes over how to create Marker maps, Heatmap maps, and Cloropleth maps. 

The dataset used for this project can be found on NYC Open Data at: https://data.cityofnewyork.us/Environment/Natural-Gas-Consumption-by-ZIP-Code-2010/uedp-fegm. I used an edited version of this dataset, with the latitude, longitude, and zip codes in seperate columns. The edited dataset can be downloaded from this repository and is titlied: Natural_Gas_Consumption_by_ZIP_Code_-_2010_clean.csv. The zipfile: Borough Boundaries (Water Areas Included).zip contains the NYC Boroughs shapefile that is needed to make the Cloropleth map. 

This project is best done as a Jupyter Notebook file. You could work through this project as the event is going on with the How to Create Maps in Python using Folium Worksheet.ipynb file. This file depends on a few Python packages that are not available with the standard Jupyter Notebook packages. These requirments can be seen in the requirments.txt. These requirments include:

numpy==1.19.5<br/>
geopandas==0.6.1<br/>
folium==0.12.0<br/>
pandas==1.1.5<br/>
Shapely==1.6.4.post2<br/>
python==3.6.12

It is important to make sure that the right version of Python is installed as later versions of Python may not work with these packages. Also, setting up a virtual enviroment for this project could help to make sure the right versions of each package are installed. 

Information about virtual enviroments can be found in the Anaconda documentation: https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/. 

Information for installing packages: https://docs.anaconda.com/anaconda/user-guide/tasks/install-packages/.









