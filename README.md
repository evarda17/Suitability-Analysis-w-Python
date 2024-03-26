# Suitability-Analysis-w-Python
## Readme

### Project Description
*** 
This project aims to analyze the suitability of different neighborhoods in Boston for a family of four looking for a rental apartment. The analysis is based on four indicators: housing rental price, access to public schools, hospital proximity and quality, and crime rates. The project uses geospatial data to visualize the results and provide recommendations on the best locations for the family to consider.
### Methods and Data
***
The analysis is performed using Python 3. The project uses Jupyter Notebook to combine, clean and analyze the data. The following packages were used:
*	geopandas
*	pandas
*	numpy
*   matplotlib.pyplot
*	shapely.geometry.Point
*	requests
*	json
*	zipfile.ZipFile
*	math
*	folium
*	seaborn
*	matplotlib.dates
*	matplotlib.cm.viridis
*	folium.plugins.HeatMap
*  	matplotlib.colors.Normalize
*	folium.Choropleth
*	folium.Circle
* 	folium.Marker
*	folium.plugins.HeatMap
*	folium.plugins.MarkerCluster
*	mpl_toolkits.axes_grid1.make_axes_locatable
*	sklearn.preprocessing.MinMaxScaler
*	contextily
	
##### The project uses data from multiple sources, including:
*	The City of Boston's Open Data Portal: https://data.boston.gov/
*	Hospital Compare: https://data.medicare.gov/data/hospital-compare
*	Crime Incident Reports: https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system

##### The data files used in the project are located in the data directory. Here is a brief overview of each file:
*	housing_data.csv: This file contains data on the rental prices of properties in different neighborhoods in Boston for the year of 2023 (Jan-Apr).
*	public_schools.csv: This file contains data on public schools in Boston, including their location and type.
*	hospital_locations.csv: This file contains data on hospitals in Massachusetts, including their location and name.
*	crime.csv: This file contains data on crime incidents in Boston from August 2015 to present, including the location and type of crime.

The data was preprocessed in the Jupyter Notebook using Pandas and Geopandas to remove unwanted columns, combine datasets, merge data frames and transform them to geodataframes. The cleaned data was then used to perform the suitability analysis.

### Running the Project Notebook
***
To run the project notebook, follow these instructions:
1.	Install Python 3 and Jupyter Notebook on your computer.
2.	Clone the project repository to your local machine.
3.	Open Jupyter Notebook and navigate to the cloned repository.
4.  Open the UEP239_FinalProject_Eliza.ipynb file to view the notebook.
5.	Run the notebook cells in order to reproduce the analysis and results.
	
### Conclusion
***
This project provides a comprehensive analysis of the suitability of different neighborhoods in Boston for a family of four looking for a rental apartment. The results are based on multiple indicators and provide valuable insights for families who are considering moving to Boston.


