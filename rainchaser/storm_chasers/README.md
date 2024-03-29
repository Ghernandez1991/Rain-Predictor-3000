# Rainfall Prediction Final Project
Dan Smart, Abiel Ogbe, Gabe Hernandez, Brandon Coleman, Suresh Sreerameneni, and Sasi Vutukuru

## Data Acquisition
-Data Set Link - https://www.kaggle.com/noaa/gsod

-Used BigQuery from Google Cloud Services to create a query to merge data on station ID(MBAN).

-Used name, state, lat, lon, year, mo, da, temp, max, min, rain_drizzle, snow_ice_pellets, hail, thunder, tornado_funnel_cloud. All other columns were dropped.

-Only used 'CA', 'MO', 'NY', 'TX', 'FL', 'PA', 'IL', 'OH', 'GA', 'GA', 'NC', and 'MI' to limit the size of the data set to under 1 GB.

-Data was downloaded through Google Drive to a local flash drive.

## Backend
-SQLite for backend storage.

-Machine learning will be limited to Missouri to narrow the scope.

-Linear regression for temperature and classification for rain, snow, hail, thunder, and tornado.

-multivariate linear regression-
Predict temperature based on the previous weather data from station the user selects

-classification-
Predict rain or no rain based on previous weather data for the day the app is used. 

## Frontend
-Created a webpage using HTML, CSS, and JavaScript

-Integrated Tableau into the webpage for data story and vizualizations.

-Machine learning interface will be used in partnership with Missouri specific Tableau map.
