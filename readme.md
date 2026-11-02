# GIST5300 Assignment 7: Add new data to US State Income Tax Dashboard
## Author: Carson Liesik
### Date: 11/01/2026

To complete this assignment I decided to add unemployment rates to the bootstrap table. The data can be found at the following restURL:

<https://services.arcgis.com/P3ePLMYs2RVChkJx/ArcGIS/rest/services/ACS_Employment_Status_Boundaries/FeatureServer/0>

The variable code for the unemployment rate percentages is "B23025_calc_pctUnempE". Additionally, I noticed that the median income
data was missing in the orignal code from the class demo for Wyoming. Looking at the layer in the ESRI Map Viewer, I saw that it 
was because the data included Puerto Rico and Washington DC. This was probably filtering out the Wyoming values, so I added a 
filter to both the Unemployment Rate and Median Income Layers to filter out both records. This fixed the issue and now displayed
Wyoming data for each layer in the table. 

You can find the link to my updated dashboard here:

<https://cliesik51.github.io/LiesikGIST5300Assign7/>