# Reproduction Instructions 
All data used in this project is available in the data folder. The data can be processed using the notebooks in numerical order. The environment used is available as a .yml file. 

## Downloading the Data
###### NOAA 
If you would like to download the data from the original source please visit the [Climate Data Online Search](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND). And set the boxes as follows: 
- Select Weather Observation Type/Dataset: Daily Summaries       
- Select Date Range: Use the date of the hurricane you would like to look at (i. e. Ian 9/28/2022 to 9/29/2022)       
- Search For: States       
- Enter a Search Term: Florida      
Then add the dataset to cart and checkout. Download as CSV and adjust dates. Unders Station Detail check Geographic Location and Select Datatypes of AWND and WSF2. Then submit the order and receive it to your email. 
###### Zillow 
If you would like to download the data from the original source please visit [Zillow’s Housing Data](https://www.zillow.com/research/data/). Under the Home Values section can be downloaded the three datasets used for this project, please assure to select city: 
- ZHVI All Homes- Top Tier Times Series ($)     
- ZHVI All Homes - Bottom Tier Times Series ($)      
- ZHVI All Homes (SFR, condo, Co-op) - Times Series, Smoothed, Seasonally Adjusted ($)        

## Libraries 
**Pandas**: Python Data Analysis Library     
**NumPy**: For working with arrays       
**Matplotlib**: For visualization      
**Seaborn**: For visualization             
**SHAP**: Used to explain output of machine learning models                  
**Scikit Learn**: For machine learning                
**Scipy**: For scientific and mathematical problems                 
**XGBoost**: Optimized distributed gradient boosting library              
**Geopy**: Used for locating addresses from coordinates                





