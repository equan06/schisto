
For LSMS data dicts: search the country name here.
[LSMS Microdata](http://microdata.worldbank.org/index.php/catalog/lsms)

## Raw Data
Relevant raw data is in lsms_data/country_name.

## Results
Results by country are in /results.

## Shapefiles
[GADM](https://gadm.org/index.html)

## Data Dict.
### Ethiopia
Statistics are computed by % usage by households per zone.


* gahi_pub_yr: GAHI study publication year
* lsms_start_yr: LSMS start year
* lsms_end_yr: LSMS end year

GAHI
* prevalence: schistosomiasis prevalence 
* num_positive: number of positive cases 
* num_examined: number of examined people

Fertilizer (averages)
* fert: Was fertilizer used?
* urea: Was Urea used?
* dap: Was DAP used?
* manure: Was manure used?
* compost: Was compost used?
* organic_fert: Was organic fertilizer used (survey question)?
* organic_fert_dummy: Was organic fertilizer used (dummy var containing manure+compost+organic_fert)?
* inorganic_fert_dummy: Was inorganic fertilizer used (dummy var containing urea+dap)?
* fert_dummy: Was fertilizer used (dummy var containing all of above)?
* num_hh_fert: Number of households per zone

Pesticide/Herbicide/Fungicide (averages)
* prevention: Was any method of prevention used?
* pest: Was pesticide used?
* herb: Was herbicide used?
* fung: Was fungicide used?
* num_hh_phf: Number of households per zone

