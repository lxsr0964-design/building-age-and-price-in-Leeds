# building-age-and-price-in-Leeds
The research question of this report is: Is there an association between building age and price in Leeds?

## This is the assignment for GEOG5990M. 

Its purpose is to analyze the relationship between house prices in Leeds and the building years.

## files

1a.xlsx :The median price of the processed houses(LSOA)(Office of National Statistics)

APHS_EW_LSOA_2024.csv :house age(LSOA)(https://datadaptive.com/)

leeds.geojson :Leeds map(LSOA)(Office of National Statistics)

Spatial data science report.ipynb - Colab :PDF coding

Spatial_data_science_report.ipynb :this is ##python## coding

README :this


## how to run

Download all files 

Open Spatial_data_science_report.ipynb in Jupyter Notebook or Google Colab.

Run

##Code explanation

1. The package needs to be downloaded.
  
2. The downloaded data file for this project covers all LSOAs in England and Wales. The file is large and requires data extraction.
 
3. The median house prices have missing data, which are represented by ":". Manual cleaning is required for these missing values.
   
4. Box plots are generated for house prices and house ages.
   
5. House ages are categorized into 16 groups, and house prices are divided into 10 groups. A gradient color map is generated, which is color blindness-friendly.

## Acknowledgements

Thank you to the teaching team of GEOG5990M
