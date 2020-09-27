# covid-foodworkers

This repo contains code for the analysis in [Trump attacks them. COVID-19 threatens them. But immigrants keep the U.S. fed.](tktk), a Center for Public Integrity story about the disproportionate impact of COVID-19 on immigrant foodworkers who produce the vast majority of the U.S. food supply.

It was published on September 28, 2020 in parternship with Mother Jones.

## Here's what's in this repo:

### [covid-immigrant-foodworkers.Rmd](covid-immigrant-foodworkers.Rmd)
This R Makdown notebook contains code used to analyze the ethnic and nativity breakdown of front-line foodworkers, primarily at the public use microdata area (PUMA) and counties. The data sources used include Census Bureau 2018 five-year American Community Survey microdata collected by [IPUMS at the University of Minnesota](https://ipums.org/) and [COVID data from The New York Times](https://github.com/nytimes/covid-19-data).

### [geocorr2018.csv](data/geocorr2018.csv)
This CSV file contains the county-to-PUMA crosswalk table from the [Missouri Census Data Center](http://mcdc.missouri.edu/applications/geocorr2018.html)

### [ipums_food_production_by_puma.csv](data/ipums_food_production_by_puma.csv)
This CSV file contains PUMA-level data on the number, ethnicity and nativity of workers in front-line food production roles. The data comes from Census Bureau 2018 five-year American Community Survey microdata collected by IPUMS at the University of Minnesota.

### [ipums_food_production_by_county.csv](data/ipums_food_production_by_county.csv)
This CSV file contains county-level data on the number, ethnicity and nativity of workers in front-line food production roles. The data comes from Census Bureau 2018 five-year American Community Survey microdata collected by IPUMS at the University of Minnesota.

### [ipums_food_production_by_puma_ind_occ.csv](data/ipums_food_production_by_county.csv)
This CSV file contains PUMA-level data on the number, ethnicity, nativity, industry and occupation of workers in front-line food production roles. The data comes from Census Bureau 2018 five-year American Community Survey microdata collected by IPUMS at the University of Minnesota.

### [ipums_food_production_by_county_ind_oc.csv](data/ipums_food_production_by_county.csv)
This CSV file contains county-level data on the number, ethnicity, nativity, industry and occupation of workers in front-line food production roles. The data comes from Census Bureau 2018 five-year American Community Survey microdata collected by IPUMS at the University of Minnesota.

### [foodworkers_by_state.csv](data/ipums_food_production_by_county.csv)
This CSV file contains state-level data on the number, ethnicity and nativity of workers in front-line food production roles. The data comes from Census Bureau 2018 five-year American Community Survey microdata collected by IPUMS at the University of Minnesota.

## Other data sources:

### usa_00015.dat
This data extract can be created by navigating to [IPUMS USA](https://usa.ipums.org/usa/index.shtml) and selecting the 2018 five-year ACS sample with the following variables: STATEFIP, PUMA, US2018C_PUMA, US2018C_ST, PERWT, AGE, HISPAN, HISPAND, CITIZEN, EMPSTAT, EMPSTATD, OCC, IND, US2018C_INDP, US2018C_OCCP, and the following cases: AGE >= 16 and EMPSTATD = At work; Has job, not working.

### tl_2019_us_county.shp
This shapefile can be found [here](https://www2.census.gov/geo/tiger/TIGER2019/COUNTY/tl_2019_us_county.zip).

### ipums_puma_2010.shp
This shapefile can be found [here](https://usa.ipums.org/usa/resources/volii/shapefiles/ipums_puma_2010.zip)

#### Questions?
For questions about the contents of this repo, email [Joe Yerardi](https://publicintegrity.org/author/joe-yerardi/) at jyerardi@publicintegrity.org.
