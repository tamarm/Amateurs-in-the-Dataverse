# Amateurs-in-the-Dataverse
Analysis of Toronto's Public crime and  Public space

This reporsitory reviews Toronto's public data on bike and car theft, trying 
to analyze patterns of street theft.

This project analyzes Toronto's public crime, namely car and bike thefts, 
using publicly available data. 
The analysis combines geospatial, temporal, and socio-economic data to 
uncover patterns and insights into theft incidents across the city.

## Project Structure


The project consists of five Python notebooks, two folders.

### Notebooks:

1. Geospatial_data_cleaning_and_merging.ipynb
Cleans and merges geospatial datasets.
Prepares data for analysis, including park locations and theft sites.

2. Theft_cluster_analysis.ipynb
Conducts clustering analysis on theft locations.
Identifies spatial patterns and hotspots.

3. Neighborhood_data_cleaning.ipynb
Cleans neighborhood-level socio-economic data.
Includes demographic, income, and other relevant information.
Temporal_analysis.ipynb

4. Analyzes temporal trends in theft incidents.
Explores patterns by time of day, week, and season.

5. Neighborhood_analysis.ipynb
Combines socio-economic and theft data for neighborhood-level analysis.
Investigates relationships between socio-economic factors and theft rates.

### Data Folder: 
Data folder holds 4 geospatial datasets: car theft, bike theft, 
neighborhood borders and public parks<br>
It also holds the scoio economic dataset: neighbourhood-profiles-2021-158-model.xlsx<br>
And Toronto's police crime documentation file: PSDP_Open_Data_Documentation.pdf

### interactive_maps folder:
Holds 3 folium interactive maps:
1. <a href=https://tamarm.github.io/Amateurs-in-the-Dataverse/interactive_maps/car_cluster_map.html>Car clusters:</a><br>
BDSCAN car clusters and noise.<br>
Cluster tooltip and color reflect size of cluster
3. <a href=https://tamarm.github.io/Amateurs-in-the-Dataverse/interactive_maps/bike_cluster_map.html>Bike clusts:</a><br>
BDSCAN bike clusters and noise.<br>
Cluster tooltip and color reflect size of cluster
4. <a href=https://tamarm.github.io/Amateurs-in-the-Dataverse/interactive_maps/bike_price_cluster_map.html>Bike price clusters:</a><br>
BDSCAN bike clusters without noise.<br>
Cluster tooltip and color reflect average value of bikes stolen

### Data Attribution

| Data Source                   | Description                                   |
|-------------------------------|-----------------------------------------------|
| Geospatial_data_cleaning...   | Theft data cleaned by Wisdom and Tamar,<br>Geospatial cleaning and merging by Tamar|
| Toronto Neighborhood Profiles | Written by Tomer|
| Temporal analyis              | Written by Wisdom|      
| Neirborhood analysis          | Written by Tomer |
| Theft_cluster_analysis        | Written by Tamar |


## Data Sources
Publicly available datasets from the City of Toronto.
For convinence copied locally under the data folder

## Usage
Clone the repository:<br>
git clone https://github.com/tamarm/Amateurs-in-the-Dataverse.git<br>
cd Amateurs-in-the-Dataverse<br>
Run the notebooks in order to reproduce the analysis:<br>
Start with Geospatial_data_cleaning_and_merging.ipynb.<br>
Follow with the other notebooks based on your area of interest.<br>

## Insights
This project provides insights into:

Theft hotspots and clustering.
Temporal trends and high-risk times.
Neighborhood socio-economic factors related to theft patterns.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the analysis or add new features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

