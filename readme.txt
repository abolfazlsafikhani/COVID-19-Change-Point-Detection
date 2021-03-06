# Code for “NON-STATIONARY SPATIO-TEMPORAL MODELING OF COVID-19 PROGRESSION IN THE U.S.”

## Simulation

Code for reproduce simulation results can be found in the [simulation.R]. 

## Real data

### example file

[Example.pdf] provides instruction and an example of COVID-19 data analysis.

#### State-Level 

Code for reproduce state-level results can be found in the [Covid-19-state.R]  and [Covid-19-state-prediction.R]. The second file produces the results of prediction (out-of-sample MRPE and predicted values). The first file generates the rest results.

[State-level COVID-19 data](states-08-18.csv) can be found in the [New York times repository](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-states.csv)


[State-level population data](co-est2019-alldata.csv) is extracted from [National Bureau of Economic Research](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv)


[State-level distance data](sf12010statedistancemiles.csv) can be found in the [US Census Bureau](http://data.nber.org/distance/2010/sf1/state/sf12010statedistancemiles.csv)


#### County-Level 

Code for reproduce county-level results can be found in the [Covid-19-county.R]  and [Covid-19-county-prediction.R]. The second file produce the results of prediction (out-of-sample MRPE and predicted values). The first file generates the rest results.

[County-level  COVID-19](counties-08-18.csv) data can be found in the [New York times repository](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv)


[County-level population data](co-est2019-alldata.csv)is extracted from [National Bureau of Economic Research](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv)


[County-level distance data](sf12010countydistance100miles.csv) can be found in the [US Census Bureau](http://data.nber.org/distance/2010/sf1/county/sf12010countydistance100miles.csv)