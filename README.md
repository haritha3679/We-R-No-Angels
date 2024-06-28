# We-R-No-Angels<br>
## City of Angels analysing Los Angeles crime data<br>

Participants:  Haritha Koleti, Michelle Petras, Veethika Singh, Kathleen Snider-Belinski, Carmen Wiggins<br><br>

Data was downloaded from the City of Los Angeles at this URL: https://data.lacity.org/Public-Safety/CrimeData-from-2020-to-Present/2nrs-mtv8/about_data.<br>
The data contains crime information accumulated from 2020 through the first few months of 2024<br>
The goal of this analysis is to identify patterns, trends, and factors contributing to crime in LA that would predict hotspots and understanding the factors that influence crime rates.  <br>
Analysis on the data was performed using these tools:  Pyton, Pandas, Numpy, Jupyter Notebook, Matplotlib, Plotly Dahs, Leaflet, Machine Learning, SCKit, Spark SQL, Tableau, and Heroku, with varying degrees of success.  For example:<br>
  - Spark had problems with Plotly Dash, so we chose to implement Plotly in Pandas DataFrames
  - Heroku was our choice to deploy our app, but it required purchase
  - Tableau kept deleting our work!

Based on our data set, machine learning was the path we chose.<br>
We used tuning, binning by crime type, cleansing and formatting to clean the data.<br>
Logistical regression resulted in 19% accuracy on our dataset with all features included.<br>
Random Forest got us closer to our goal with a 35% accuracy.<br>
By focusing our requests by area, gender, age and other factors individually, we were able to achieve an accuracy of 89%.  Other interesting outliers became obvious utilizing these methods, even with lower accuracy scores, and we chose to explore some of them.<br>
We then checked other models to see if we could increase any further, but Random Forest was the highest or equal score.<br>


Files are located in https://github.com/haritha3679/We-R-No-Angels<br>

<strong>Work process:</strong> Filename<br>
<strong>Machine learning:</strong> Crime_analysisRF_tune.ipynb<br>
<strong>Spark, Dash:</strong>  Crime_data_imp_dash.ipynb<br>
<strong>Outliers:</strong> Outliers.ipynb<br>
<strong>Crime Bins:</strong> Crime_bins.csv<br>

### Links
<strong>Tableau</strong><br>
  - https://public.tableau.com/authoring/DashboardProject4_17193531816340/Dashboard1#1<br>
  - https://public.tableau.com/app/profile/carmen.wiggins/viz/DashboardProject4_17193531816340/Dashboard1<br>

<br><strong>Crime Map</strong><br>
  - https://github.com/petrick312/la_crime_map<br>

