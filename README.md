# Household income in contiguous US
### Python project with geopandas mapping.
The project uses kaggle [dataset](https://www.kaggle.com/datasets/claygendron/us-household-income-by-zip-code-2021-2011) on median and mean US household incomes.
Data is visualized using geopandas library and US census [shape files](https://www2.census.gov/geo/tiger/TIGER2020/ZCTA520). The resulting map shows income by zip code.
Here is the resulting map: ![Map](images/Map.png?raw=true)  
Looks like resolution by zip code gives a bit too detailed view, on the other hand resolution on state level is too generalized. Probably it makes sence to make smaller maps when working with zip codes, for example separate map for each state, but that requires different datasets.
