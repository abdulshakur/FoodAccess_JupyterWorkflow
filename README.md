# FoodAccess_JupyterWorkflow
Jupyter notebook I used to follow the USDA's Food Environment Atlas indicators data for possible causes

Motivation:
I wanted to see if the USDA’s Food Atlas dataset would show any correlation between reduced access to food and increased adverse health events.

The following links contain the original data sources:
I used the following data sources
https://www.ers.usda.gov/data-products/food-environment-atlas/documentation/
https://www.healthdata.gov/dataset/community-health-status-indicators-chsi-combat-obesity-heart-disease-and-cancer
https://www.kaggle.com/mikejohnsonjr/united-states-crime-rates-by-county

USDA Food Environment Atlas indicators, grouped under the following categories:

Access and Proximity to Grocery Store
Store Availability
Restaurant Availability and Expenditures
Food Assistance
State Food Insecurity
Food Prices and Taxes
Local Foods
Health and Physical Activity
Socioeconomic Characteristics

Data sources: In each of the referenced reports, a directory of supermarkets and large grocery stores authorized to accept SNAP benefits was merged with Trade Dimensions' TDLinx directory of stores within the United States, including Alaska and Hawaii, for the years 2010 and 2015. Stores met the definition of a supermarket or large grocery store if they reported at least $2 million in annual sales and contained all the major food departments found in a traditional supermarket, including fresh meat and poultry, dairy, dry and packaged foods, and frozen foods. The combined list of supermarkets and large grocery stores was converted into a GIS-usable format by geocoding the street address into store-point locations. Population data are reported at the block level from the 2010 Census of Population and Housing. These population data were aerially allocated down to ½-kilometer-square grids across the United States. For each ½-kilometer-square grid cell, the distance was calculated from its geographic center to the center of the grid cell with the nearest supermarket. Rural or urban status is designated by the Census Bureau’s Urban Area definition.

Health Data

Community Health Status Indicators (CHSI) to combat obesity, heart disease, and cancer are major components of the Community Health Data Initiative. This dataset provides key health indicators for local communities and encourages dialogue about actions that can be taken to improve community health (e.g., obesity, heart disease, cancer). The CHSI report and dataset was designed not only for public health professionals but also for members of the community who are interested in the health of their community. The CHSI report contains over 200 measures for each of the 3,141 United States counties. Although CHSI presents indicators like deaths due to heart disease and cancer, it is imperative to understand that behavioral factors such as obesity, tobacco use, diet, physical activity, alcohol and drug use, sexual behavior and others substantially contribute to these deaths.

Crime rates

These data provide information on the number of arrests reported to the Federal Bureau of Investigation's (FBI) Uniform Crime Reporting (UCR) Program each month by police agencies in the United States. Although not as well known as the "Crimes Known to the Police" data drawn from the Uniform Crime Report's Return A form, the arrest reports by age, sex, and race provide valuable data on 43 offenses including violent, drug, gambling, and larceny crimes. The data received  were structured as a hierarchical file containing (per reporting police agency) an agency header record, and 1 to 12 monthly header reports, and 1 to 43 detail offense records containing the counts of arrests by age, sex, and race for a particular offense. The data has been restructured from the original data to a rectangular format.
